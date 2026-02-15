# Awesome Magento 2 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 437,495 | 🐛 70 | 📅 2026-01-28[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) with stars

<div align="center">
	<a href="https://vshymanskyy.github.io/StandWithUkraine">
		<img width="500" height="350" src="media/logo-ua.svg" alt="Awesome">
		<img src="https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg">
	</a>
	<br>
	<br>
	<br>
	<br>
	<hr>
</div>

> A curated list of awesome Magento 2 Extensions & Resources.

* [What is an awesome list?](https://github.com/sindresorhus/awesome/blob/master/awesome.md) ⭐ 437,495 | 🐛 70 | 📅 2026-01-28
* [Contribution guide](origin/contributing.md) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/DavidLambauer/awesome-magento2/issues) ⭐ 1,164 | 🐛 7 | 🌐 PHP | 📅 2025-07-04

***

## Table of Contents

* [What is Magento?](#magento)
* [Events](#events)
* [Frontends](#frontends)
* [Tools](#tools)
* [Open Source Extensions](#open-source-extensions)
* [Blogs](#blogs)
* [Education](#learning)
* [Platforms](#platforms)
* [Official Resources](#official-resources)

***

## What is Magento?

Magento is an open-source e-commerce application that allows you to create webshops. We often speak of a frontend (the
storefront where customers buy products) and a backend (the Magento Admin Panel where customers and products are being
managed). The open source bit refers to the fact that the source code of Magento (PHP, HTML, CSS, JS, XML, and others)
is distributed under an open-source license (OSLv3) that allows anyone to reuse the code and make changes to it. This
open-source aspect has led to the massive popularity of the product Magento so that we often use the word Magento to
refer to either the product, the community around it or both.

Magento was started by a company called Varien, and with Magento version 1 (first released in 2008), popularity began to grow.
Magento version 2 was first released in November 2015 but faced a problematic adoption because of its complex
architecture and outdated features (KnockoutJS, RequireJS, Zend Framework 1). On the storefront part,
this led to various new frontends. In 2018, Magento was acquired by Adobe. Later, Magento Enterprise was integrated
into the Adobe cloud as Adobe Commerce Cloud, while the Magento Community Edition was relabeled Magento Open Source. In
the community, there was uncertainty whether Adobe would maintain Magento Open Source in the long run in the way
the community would see fit. This uncertainty led to a community initiative called Mage-OS.

Also see:

* [en.wikipedia.org/wiki/Magento](https://en.wikipedia.org/wiki/Magento)

## Events: Meet the community

* [MageUnconference 🇩🇪](https://www.mageunconference.org/) - A Magento Unconference in Germany.
* [MageUnconference 🇳🇱](https://mageunconference.nl/) - A Magento Unconference in the Netherlands.
* [Meet Commerce](https://www.meetcommerce.com/) - A global series of conferences focused on commerce and innovation.

### Meet Magento

[Meet Magento events](https://www.meet-magento.com/) bring together everyone from merchants through developers, solution and technology providers, and
marketers—and we continue to expand.

* [Meet Magento Baltics](https://meetmagentobaltics.com/)
* [Meet Magento Brazil](https://meetmagentobrasil.org/)
* [Meet Magento Florida](https://meetmagentofl.com/)
* [Meet Magento India](https://www.meetmagento.in/)
* [Meet Magento Malaysia](https://www.meetmagento.asia/)
* [Meet Magento Netherlands](https://nl.meet-magento.com/)
* [Meet Magento New York City](https://meetmagentonyc.com/)
* [Meet Magento Poland](https://meetmagento.pl/)
* [Meet Magento Romania](https://ro.meet-magento.com/)
* [Meet Magento Singapore](https://meetmagento.sg/)
* [Meet Magento UK](https://meet-magento.co.uk/)

## Front-ends

The storefront of Magento 2 can be styled in numerous ways:

* **Alokai** (*ex: Vue Storefront*) ([github.com/vuestorefront/vue-storefront](https://github.com/vuestorefront/vue-storefront) ⭐ 10,907 | 🐛 52 | 📅 2026-02-13)
* **ScandiPWA** ([github.com/scandipwa/scandipwa](https://github.com/scandipwa/scandipwa) ⭐ 553 | 🐛 535 | 🌐 TypeScript | 📅 2024-07-15)
* **Luma** (`Magento/luma`) - This is actually a default demo theme of Magento 2 itself, which again extends from `Magento/blank` which extends from the core. But more often, the name Luma refers to the entire stack: XML layout generates a tree-structure of blocks and containers, which eventually render via PHTML templates. The server-side rendered HTML is enriched with CSS (compiled from LESS source files) and JavaScript (RequireJS, KnockoutJS, jQuery).
* **Adobe PWA Studio** - A new headless frontend, created by Adobe/Magento, based on ReactJS. It makes GraphQL calls to the Magento GraphQL API to retrieve data. The frontend offers Venia (a demo theme and UI component library), Peregrine (React hooks), Buildpack (Webpack configuration) and UPWARD (a middleware for SSR and image optimization).
* **Hyvä** ([hyva.io](https://hyva.io/)) - An alternative for Luma, which replaces the LESS/CSS with TailwindCSS and the JavaScript with AlpineJS. Currently, it is only available via a commercial license. But for that price, the team works hard to create compatibility modules for 3rd party modules, give support and make the entire solution more and more versatile.
* **DEITY**
* **Breeze Evolution** ([breezefront.com](https://breezefront.com/themes)) - A 100 pagespeed score frontend theme that is compatible with all Luma-based extensions.
* **Front-Commerce** ([front-commerce.com](https://www.front-commerce.com/))- Front-Commerce is an innovative, advanced, ready-to-use PWA (Progressive Web App) front-end solution developed in France for Magento stores.

## Tools

* [PhpInsights](https://github.com/nunomaduro/phpinsights) ⭐ 5,578 | 🐛 72 | 🌐 PHP | 📅 2025-11-12 - PHP quality checks (with Magento2 presets)
* [DDEV](https://github.com/ddev/ddev) ⭐ 3,493 | 🐛 149 | 🌐 Go | 📅 2026-02-14 - A open source tool for launching local web development environments in minutes. It supports PHP, Node.js, and Python.
* [markshust/docker-magento](https://github.com/markshust/docker-magento) ⭐ 2,830 | 🐛 25 | 🌐 Shell | 📅 2026-02-09 - Mark Shust's Docker Configuration for
  Magento
* [n98-magerun2](https://github.com/netz98/n98-magerun2) ⭐ 922 | 🐛 28 | 🌐 PHP | 📅 2026-02-14 - The CLI Swiss Army Knife for Magento 2.
* [Pestle](https://github.com/astorm/pestle) ⭐ 532 | 🐛 184 | 🌐 PHP | 📅 2023-04-19 - Code Generation Tool by Alan Storm.
* [PhpStorm Magento2 Extension](https://github.com/magento/magento2-phpstorm-plugin) ⭐ 454 | 🐛 103 | 🌐 Java | 📅 2025-11-15 - Official PhpStorm Magento2
  Extension.
* [Warden](https://github.com/wardenenv/warden) ⭐ 451 | 🐛 37 | 🌐 Shell | 📅 2026-02-12 - A CLI utility for working with docker-compose environments
  by [David Alger](https://davidalger.com/)
* [Mage Chrome Toolbar](https://github.com/magespecialist/mage-chrome-toolbar) ⭐ 336 | 🐛 14 | 🌐 JavaScript | 📅 2024-04-22 - A MUST-HAVE Chrome Extension for
  Magento 2 by [MageSpecialist](https://github.com/magespecialist).
* [AmpersandHQ/ampersand-magento2-upgrade-patch-helper](https://github.com/AmpersandHQ/ampersand-magento2-upgrade-patch-helper) ⭐ 334 | 🐛 8 | 🌐 PHP | 📅 2024-11-11 - Helper script to aid upgrading magento 2 websites by detecting overrides.
* [Magento 2 Url Data Integrity Checker](https://github.com/baldwin-agency/magento2-module-url-data-integrity-checker) ⭐ 280 | 🐛 8 | 🌐 PHP | 📅 2026-01-30 - Magento 2 module which can find potential url related problems in your catalog data
* [Masquerade](https://github.com/elgentos/masquerade) ⚠️ Archived - Faker-driven, configuration-based, platform-agnostic,
  locale-compatible data faker tool
* [MageSpecialist DevTools for Magento 2](https://github.com/magespecialist/m2-MSP_DevTools) ⭐ 222 | 🐛 13 | 🌐 PHP | 📅 2024-06-20 Developer Toolbar
* [Tango](https://github.com/roma-glushko/tango) ⭐ 113 | 🐛 23 | 🌐 Go | 📅 2023-02-19 - CLI for analyzing access logs
* [Migrate DB Magento 2 Commerce to Magento 2 Open-Source](https://github.com/opengento/magento2-downgrade-ee-ce) ⭐ 88 | 🐛 4 | 📅 2025-11-17
* [Magento 2 Database Synchronizer](https://github.com/jellesiderius/mage-db-sync) ⭐ 81 | 🐛 3 | 🌐 TypeScript | 📅 2026-01-28 - Database synchronizer for Magento 2 (and Wordpress), based on Magerun2. Keeping development, staging and production in sync easily.
* [Subodha Magento2 Gulp Integration](https://github.com/subodha/magento-2-gulp) ⭐ 74 | 🐛 5 | 🌐 JavaScript | 📅 2021-05-10 - Magento 2 Gulp Integration
* [RabbitMQ Retry Mechanism](https://github.com/run-as-root/magento2-message-queue-retry) ⭐ 64 | 🐛 0 | 🌐 PHP | 📅 2025-10-15 - Magento 2 extension that brings possibility to retry RabbitMQ failed messages
* [Mage Wizard](https://github.com/clickAndMortar/mage-wizard) ⭐ 20 | 🐛 6 | 🌐 TypeScript | 📅 2024-05-17 - Local web UI to view and create automatically modules, plugins, configs, observers, commands, crontabs, etc. directly in Magento 2 codebase
* [Mage](https://github.com/GrimLink/mage) ⭐ 18 | 🐛 2 | 🌐 Shell | 📅 2026-02-11 - Simplifies bin/magento commands by adding helpful shortcuts and time-saving tools to enhance your productivity.
* [MageForge](https://github.com/OpenForgeProject/mageforge) ⭐ 14 | 🐛 3 | 🌐 PHP | 📅 2026-02-14 - Magento 2 Cli automatic Theme(s) Builder (Hyvä ready)
* [Documentation Search for Alfred](https://github.com/DavidLambauer/Alfred-Workflow-Magento-2-DevDocs-Search) ⭐ 10 | 🐛 1 | 📅 2016-11-19 - Easily
  integrate the official Magento 2 Search into your Alfred Workflows.
* [magento2docker](https://github.com/aliuosio/magento2docker) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-03-31 - MariaDB, PHP , Redis, ElasticSearch in one dockerfile for fast demo and deveopment enviroment
* [Tablerates Generator](https://www.tableratesgenerator.com/) - Generate Tablerates with an online Tool.
* [Mage2Gen](https://mage2gen.com/) - Online Module Creator.
* [Magento 2 Composer patches helper](https://chrome.google.com/webstore/detail/magento-2-composer-patche/gfndadbceejgfjahpfaijcacnmdloiad) - Chrome extension to create copy-pastable composer patch definition for vaimo/composer-patches.
* [Magento Log Viewer - A Visual Studio Code Extension ](https://marketplace.visualstudio.com/items?itemName=MathiasElle.magento-log-viewer) - Provides a convenient way to view, watch and manage Magento log files and reports directly in your workspace.

## Open Source Extensions

### Development Utilities

* [Magento Cache Clean](https://github.com/mage2tv/magento-cache-clean) ⭐ 543 | 🐛 14 | 📅 2025-07-11 - A faster drop in replacement for bin/magento
  cache:clean with file watcher by Vinai Kopp]\(<https://twitter.com/vinaikopp>)
* [Developer Toolbar](https://github.com/mgtcommerce/Mgt_Developertoolbar) ⭐ 308 | 🐛 2 | 🌐 PHP | 📅 2023-12-11 - Magento 2 Developer Toolbar.
* [Advanced Template Hints](https://github.com/ho-nl/magento2-Ho_Templatehints) ⭐ 288 | 🐛 22 | 🌐 PHP | 📅 2025-05-12 - Magento 2 Template Hints Helper.
* [MageVulnDB](https://github.com/gwillem/magevulndb) ⭐ 208 | 🐛 10 | 🌐 PHP | 📅 2026-01-23 - Central repository for third party Magento extensions with known
  security issues.
* [Magento 2 Configurator](https://github.com/ctidigital/magento2-configurator) ⭐ 174 | 🐛 22 | 🌐 PHP | 📅 2025-10-15 - A Magento module initially created by
  CTI Digital to create and maintain database variables using files.
* [Cypress Testing Suite](https://github.com/elgentos/magento2-cypress-testing-suite/) ⭐ 173 | 🐛 19 | 🌐 JavaScript | 📅 2024-03-28 - A community-driven Cypress
  testing suite for Magento 2
* [Scope Hints](https://github.com/avstudnitz/AvS_ScopeHint2) ⭐ 166 | 🐛 6 | 🌐 PHP | 📅 2025-05-05 - Displays additional information in the Store Configuration
  by Andreas von Studnitz.
* [Config ImportExport](https://github.com/semaio/Magento2-ConfigImportExport) ⭐ 162 | 🐛 4 | 🌐 PHP | 📅 2024-08-28 - CLI Based Config Management.
* [bitExpert/phpstan-magento](https://github.com/bitExpert/phpstan-magento) ⭐ 147 | 🐛 13 | 🌐 PHP | 📅 2025-09-27 - Magento specific extension for PHPStan
* [Whoops Exceptions](https://github.com/yireo/Yireo_Whoops) ⭐ 102 | 🐛 3 | 🌐 PHP | 📅 2026-01-28 - PHP Exceptions for Cool Kids in Magento 2.
* [graycoreio/magento2-cors](https://github.com/graycoreio/magento2-cors) ⭐ 98 | 🐛 1 | 🌐 PHP | 📅 2026-01-21 - Enables configurable CORS Headers on the
  Magento GraphQL API.
* [Magento 2 Prometheus Exporter](https://github.com/run-as-root/magento2-prometheus-exporter) ⭐ 68 | 🐛 5 | 🌐 PHP | 📅 2025-12-28 - Prometheus Exporter for
  common Magento Data.
* [Magento 2 PHPStorm File Templates](https://github.com/lfolco/phpstorm-m2-filetemplates) ⭐ 42 | 🐛 2 | 🌐 HTML | 📅 2022-12-21 - PHPStorm Magento 2 File
  Templates.
* [Auto Cache Flush](https://github.com/yireo/Yireo_AutoFlushCache) ⭐ 28 | 🐛 1 | 🌐 PHP | 📅 2023-09-27 - Magento 2 module to automatically flush the cache.
* [Dot Env](https://github.com/zepgram/magento-dotenv) ⭐ 13 | 🐛 0 | 🌐 PHP | 📅 2024-02-12 - Magento 2 Environment Variable Component - Implementing Symfony Dotenv.
* [Rest Client](https://github.com/zepgram/module-rest) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - Technical Magento 2 module providing simple development pattern, configurations and optimizations to make REST API requests toward external services based on Guzzle Client.
* [Yireo LokiComponents](https://github.com/yireo/Yireo_LokiComponents) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2026-02-13 - A library for building AJAX-driven form components with ease. Used by the Yireo Loki Checkout.
* [Magento 2 Model Generator / CRUD Generator](https://www.model-generator.com/) - A more up-to-date version of a Magento 2 Model & CRUD Generator by [Michiel Gerritsen](https://github.com/michielgerritsen)
* [Simon's Troubleshooting Guide](https://gist.github.com/ProcessEight/000245eac361cbcfeb9daf6de3c1c2e4) - A list with the most common errors you encounter during development.
* [Magewire PHP](https://github.com/magewirephp) - A Laravel Livewire port for building complex AJAX-based components with ease. Used by the Hyvä Checkout.

### Deployment

* [Deployer Magento2 Recipe](https://github.com/deployphp/deployer/blob/master/recipe/magento2.php) ⭐ 11,003 | 🐛 7 | 🌐 PHP | 📅 2026-02-05 - Magento2
  deployment recipe for [deployer](https://deployer.org/).
* [Magento 2 Deployer Plus](https://github.com/jalogut/magento2-deployer-plus) ⭐ 201 | 🐛 13 | 🌐 PHP | 📅 2022-10-03 - Tool based on deployer.org to perform
  zero downtime deployments of Magento 2 projects.
* [Github Actions for Magento2](https://github.com/extdn/github-actions-m2) ⭐ 139 | 🐛 14 | 🌐 Shell | 📅 2026-01-20 - GitHub Actions for Magento 2 Extensions

### Localization

* [de\_DE](https://github.com/splendidinternet/Magento2_German_LocalePack_de_DE) ⭐ 86 | 🐛 10 | 🌐 PHP | 📅 2023-07-18 :de: - German Language Package.
* [pt\_BR](https://github.com/rafaelstz/traducao_magento2_pt_br) ⭐ 73 | 🐛 3 | 🌐 PHP | 📅 2023-03-15 🇧🇷 - Portuguese Brazil Language Package.
* [fr\_FR](https://github.com/Imaginaerum/magento2-language-fr-fr) ⭐ 41 | 🐛 113 | 🌐 PHP | 📅 2021-02-08 :fr: - French Language Package.
* [tr\_TR](https://github.com/hidonet/magento2-language-tr_tr) ⭐ 32 | 🐛 0 | 🌐 PHP | 📅 2019-08-04 :tr: - Turkish Language Package.
* [pl\_PL](https://github.com/SnowdogApps/magento2-pl_pl) ⭐ 17 | 🐛 0 | 🌐 PHP | 📅 2024-10-15 🇵🇱 - Polish Language Package.
* [it\_IT](https://github.com/mageplaza/magento-2-italian-language-pack) ⭐ 15 | 🐛 19 | 🌐 PHP | 📅 2024-03-21 :it: - Italian Language.
* [es\_ES](https://github.com/eusonlito/magento2-language-es_es) ⭐ 14 | 🐛 3 | 🌐 PHP | 📅 2020-08-07 :es: - Spanish Language Package.
* [sl\_SI](https://github.com/symfony-si/magento2-sl-si) ⭐ 11 | 🐛 6 | 🌐 PHP | 📅 2018-05-27 🇸🇮 - Slovenian Language Package.
* [nl\_NL](https://github.com/magento-l10n/language-nl_NL) ⭐ 8 | 🐛 4 | 🌐 PHP | 📅 2025-05-05 🇳🇱 - Dutch Language Package.
* [ro\_RO](https://github.com/EaDesgin/magento2-romanian-language-pack) ⭐ 8 | 🐛 4 | 🌐 PHP | 📅 2021-04-29 🇷🇴 - Romanian Language Package.
* [de\_CH](https://github.com/staempfli/magento2-language-de-ch) ⭐ 7 | 🐛 5 | 🌐 PHP | 📅 2022-04-08 🇨🇭 - Swiss Language Package.
* [ko\_KR](https://github.com/mageplaza/magento-2-korean-language-pack) ⭐ 4 | 🐛 4 | 🌐 PHP | 📅 2022-02-22 🇰🇷 - Korean Language Package.
* [en\_GB](https://github.com/cubewebsites/magento2-language-en-gb) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2021-04-28 :gb: - British Language Package.
* [es\_AR](https://github.com/SemExpert/Magento2-language-es_ar) ⭐ 2 | 🐛 1 | 🌐 PHP | 📅 2019-12-23 🇦🇷 - Spanish (Argentina) Language Package.
* [fi\_FL](https://github.com/mageplaza/magento-2-finnish-language-pack) ⭐ 0 | 🐛 3 | 🌐 PHP | 📅 2023-10-31 🇫🇮 - Finnish Language Package.
* [sk\_SK](https://github.com/mageplaza/magento-2-slovak-language-pack) ⭐ 0 | 🐛 5 | 🌐 PHP | 📅 2023-01-25 🇸🇰 - Slovakian Language Package.
* [da\_DK](https://magentodanmark.dk/) 🇩🇰 - Danish Language Package.
* [hr\_HR](https://marketplace.magento.com/inchoo-language-hr-hr.html) :croatia: - Croatian Language Package.

### Search

* [Elastic Suite Integration](https://github.com/Smile-SA/elasticsuite/) ⭐ 806 | 🐛 119 | 🌐 PHP | 📅 2026-02-13 - Elastic Suite Integration.
* [Algolia Search Integration](https://github.com/algolia/algoliasearch-magento-2) ⭐ 188 | 🐛 2 | 🌐 PHP | 📅 2026-02-12 - Algolia Search(SaaS) Integration.
* [FastSimpleImport2](https://github.com/firegento/FireGento_FastSimpleImport2) ⭐ 135 | 🐛 37 | 🌐 PHP | 📅 2025-01-29 - Wrapper for Magento 2 ImportExport functionality, which imports products and customers from arrays.
* [Disable Search Engine](https://github.com/zepgram/module-disable-search-engine) ⭐ 87 | 🐛 0 | 🌐 PHP | 📅 2025-05-16 - Disable Elasticsearch and fulltext indexing for category search.

### CMS

* [Magento 2 Blog Extension by Magefan](https://github.com/magefan/module-blog) ⭐ 269 | 🐛 12 | 🌐 PHP | 📅 2026-01-30 - Free Blog module for Magento 2 with
  unlimited blog posts and categories, SEO friendly, lazy load and AMP support.
* [Opengento GDPR](https://github.com/opengento/magento2-gdpr) ⭐ 143 | 🐛 8 | 🌐 PHP | 📅 2025-07-23 - Magento 2 GDPR module is a must have extension for the
  largest e-commerce CMS used in the world. The module helps to be GDPR compliant.
* [Mageplaza Blog Extension](https://github.com/mageplaza/magento-2-blog-extension) ⭐ 122 | 🐛 24 | 🌐 PHP | 📅 2025-12-31 - Simple, but well working Blog
  Extension.

### Marketing

* [Google Tag Manager](https://github.com/magepal/magento2-google-tag-manager) ⭐ 262 | 🐛 15 | 🌐 PHP | 📅 2025-06-17 - Google Tag Manager (GTM) with Data
  Layer for Magento2.
* [MagePlaza Seo](https://github.com/mageplaza/magento-2-seo-extension) ⭐ 136 | 🐛 5 | 🌐 PHP | 📅 2026-02-09 - Well documented multi purpose SEO Extension.
* [Magento 2 PDF](https://github.com/staempfli/magento2-module-pdf) ⭐ 58 | 🐛 4 | 🌐 PHP | 📅 2020-09-16 - PDF Generator based
  on [wkhtmltopdf](http://wkhtmltopdf.org/).

### Adminhtml / Backend

* [Menu Editor](https://github.com/SnowdogApps/magento2-menu) ⭐ 327 | 🐛 17 | 🌐 JavaScript | 📅 2026-01-30 - Provides powerful menu editor to replace category based
  menus in Magento 2.
* [Custom SMTP](https://github.com/magepal/magento2-gmail-smtp-app) ⭐ 325 | 🐛 5 | 🌐 PHP | 📅 2026-01-09 - Configure Magento 2 to send all transactional
  email using Google App, Gmail, Amazon Simple Email Service (SES), Microsoft Office365 and other SMTP server.
* [Disable Stock Reservation](https://github.com/AmpersandHQ/magento2-disable-stock-reservation) ⭐ 228 | 🐛 19 | 🌐 PHP | 📅 2026-01-21 - This module disables the inventory reservation logic introduced as part of MSI in Magento 2.3.3.
* [Sentry.io](https://github.com/justbetter/magento2-sentry) ⭐ 184 | 🐛 8 | 🌐 PHP | 📅 2026-01-27 - Application Monitoring and Error Tracking Software for
  Magento 2
* [Customer Force Login](https://github.com/bitExpert/magento2-force-login) ⭐ 169 | 🐛 7 | 🌐 PHP | 📅 2024-05-01 - Forces customers to log in before
  accessing certain pages.
* [Clean Admin Menu](https://github.com/redchamps/clean-admin-menu) ⭐ 162 | 🐛 0 | 🌐 PHP | 📅 2025-04-16 - Merges 3rd party extensions to a single menu.
* [FireGento Fast Simple Import](https://github.com/firegento/FireGento_FastSimpleImport2) ⭐ 135 | 🐛 37 | 🌐 PHP | 📅 2025-01-29 - Wrapper for Magento 2
  ImportExport functionality, which imports products and customers from arrays
* [Magento 2 Import Framework](https://github.com/techdivision/import) ⭐ 127 | 🐛 10 | 🌐 PHP | 📅 2025-10-24 - A library supporting generic Magento 2 import
  functionality
* [Checkout Tester](https://github.com/yireo/Yireo_CheckoutTester2) ⭐ 93 | 🐛 3 | 🌐 PHP | 📅 2024-10-24 - Extension to quickly test Checkout changes.
* [Preview Checkout Success Page](https://github.com/magepal/magento2-preview-checkout-success-page) ⭐ 77 | 🐛 3 | 🌐 PHP | 📅 2026-01-14 - quickly and
  easily preview and test your order confirmation page, without the need to placing a new order each time.
* [Guest to Customer](https://github.com/magepal/magento2-guest-to-customer) ⭐ 68 | 🐛 6 | 🌐 PHP | 📅 2026-01-07 - Quickly and easily convert existing guest
  checkout customers to registered customers.
* [shkoliar/magento-grid-colors](https://github.com/shkoliar/magento-grid-colors) ⭐ 60 | 🐛 2 | 🌐 JavaScript | 📅 2021-10-05 - Magento 2 Grid Colors module for
  colorizing admin grids. Supports saving of states with the help of grid's bookmarks.
  by [Dmitry Shkoliar](https://shkoliar.com/)
* [PageNotFound](https://github.com/experius/Magento-2-Module-PageNotFound) ⭐ 43 | 🐛 12 | 🌐 PHP | 📅 2025-12-01 - Saves upcoming 404 in your Database with
  the possibility to created a redirect.
* [Reset UI Bookmarks](https://github.com/magenizr/Magenizr_ResetUiBookmarks) ⭐ 38 | 🐛 0 | 🌐 PHP | 📅 2024-07-17 - Reset UI Bookmarks allows admin users to
  reset their own UI bookmarks such as state of filters, column positions and applied sorting ( e.g Sales > Orders ).
* [extdn/extension-dashboard-m2](https://github.com/extdn/extension-dashboard-m2) ⭐ 38 | 🐛 2 | 🌐 PHP | 📅 2022-03-23 - A Magento 2 dashboard to display
  installed extensions. by [Magento Extension Developers Network](https://extdn.org/)
* [Reset Customer Password](https://github.com/Vinai/module-customer-password-command) ⭐ 27 | 🐛 2 | 🌐 PHP | 📅 2022-06-15 - Set a customer password with
  bin/magento by [Vinai Kopp](https://github.com/Vinai/).
* [Product Links Navigator](https://github.com/elninotech/ElNino_ProductLinksNavigator) ⭐ 17 | 🐛 0 | 🌐 PHP | 📅 2025-02-27 - Enhances admin product-to-product navigation. Adds direct frontend/backend links to products in grids and modals, and "Parent Products" tab.
* [hivecommerce/magento2-content-fuzzyfyr](https://github.com/hivecommerce/magento2-content-fuzzyfyr) ⚠️ Archived - The Content
  Fuzzyfyr module for Magento2 replaces real content with dummy content. This is for development purposes, e.g. save
  time to prepare test data and matching GDPR restrictions.

### Security

* [Magento Quality Patches](https://experienceleague.adobe.com/tools/commerce-quality-patches/index.html) - Every Magento / Adobe Commerce patch you need all in one place

### Payment Service Provider

* [Stripe](https://github.com/pmclain/module-stripe) ⚠️ Archived - Stripe Payments for Magento 2.
* [PAYONE](https://github.com/PAYONE-GmbH/magento-2) ⭐ 28 | 🐛 9 | 🌐 PHP | 📅 2026-02-13 - PAYONE Payment Integration.
* [Braintree Payments](https://marketplace.magento.com/paypal-module-braintree.html) - Official Braintree Integration
  for Magento2.

### Infrastructure

* [Ethan3600/magento2-CronjobManager](https://github.com/Ethan3600/magento2-CronjobManager) ⭐ 363 | 🐛 14 | 🌐 PHP | 📅 2025-05-01 - Cron Job Manager for
  Magento 2.
* [Fastly Extension](https://github.com/fastly/fastly-magento2) ⭐ 156 | 🐛 36 | 🌐 PHP | 📅 2026-02-09 - Magento 2 fastly integration.
* [Interceptor Optimization](https://github.com/creatuity/magento2-interceptors) ⭐ 136 | 🐛 6 | 🌐 PHP | 📅 2025-04-15 - New interceptors approach for Magento 2
* [Clean Media](https://github.com/sivaschenko/magento2-clean-media) ⭐ 95 | 🐛 7 | 🌐 PHP | 📅 2024-02-07 - A Module that provides information about Media
  Files and potential removal options.
* [Magento 2 Ngrok](https://github.com/shkoliar/magento-ngrok) ⭐ 48 | 🐛 5 | 🌐 PHP | 📅 2023-05-29 - Magento 2 Ngrok Integration

***

### Proprietary Extensions

* [Commercebug Debugging Extension](http://store.pulsestorm.net/products/commerce-bug-3) - A Magento 2 Debug Extension.
* [Magicento](http://magicento.com/) - [PHPStorm](https://www.jetbrains.com/phpstorm/) Plugin to add Magento 2 related
  functionality.

***

#### Progressive Web Application

* [ScandiPWA Theme](https://github.com/scandipwa/base-theme) ⭐ 553 | 🐛 535 | 🌐 TypeScript | 📅 2024-07-15 - Magento 2.3+ PWA theme based on React and Redux

***

## Blogs

### Personal Blogs

* [Alan Storm](http://alanstorm.com/category/magento-2/)
* [Fabian Schmengler](https://www.schmengler-se.de/)
* [Jigar Karangiya](https://jigarkarangiya.com/)

### Company Blogs

* [Atwix](https://www.atwix.com/blog/)
* [Classy Llama](https://www.classyllama.com/blog)
* [dev98](https://dev98.de/)
* [FireBear Studio](https://firebearstudio.com/blog)
* [Fooman](http://store.fooman.co.nz/blog)
* [inchoo](http://inchoo.net/category/magento-2/)
* [M.academy](https://m.academy/blog/)
* [integer\_net blog](https://www.integer-net.com/blog/)
* [MageComp](https://magecomp.com/blog/category/magento-2/)
* [bitExpert AG](https://blog.bitexpert.de/blog/tags/magento)
* [OneStepCheckout](https://blog.onestepcheckout.com/)

### Other

* MageTalk: A Magento Community Podcast]\(<http://magetalk.com/>) - Community Podcast by \[Kalen Jordan and \[Phillip
  Jackson.

## Learning

* [magento-notes/magento2-exam-notes](https://github.com/magento-notes/magento2-exam-notes) ⭐ 702 | 🐛 4 | 📅 2021-08-15 - Preparation notes for
  Magento 2 Certified Professional Developer exam
* [fisheye-academy/m2cpfed-training](https://github.com/fisheye-academy/m2cpfed-training) ⭐ 114 | 🐛 1 | 📅 2020-09-30 - Resources for the Magento 2
  Certified Professional Front End Developer exam
* [magento-notes/magento2-cloud-developer-notes](https://github.com/magento-notes/magento2-cloud-developer-notes) ⭐ 85 | 🐛 0 | 📅 2019-04-10 -
  Preparation notes for Magento 2 Certified Professional Cloud Developer exam
* [roma-glushko/magento2-dev-plus-exam](https://github.com/roma-glushko/magento2-dev-plus-exam) ⭐ 76 | 🐛 0 | 🌐 PHP | 📅 2019-11-23 - Preparation notes for
  Magento 2 Certified Professional Developer Plus exam
* [M.academy](https://m.academy/) - The simplest way to learn Magento 2 & Adobe Commerce, with video lessons & courses
* [MageTitans Italia 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVP3Fm_c4HfNPK5JdRD6DIDl)
* [MageTitans MCR 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVMOnBRS49ICbNWOU5jhNNWC)
* [MageTitans USA/Texas 2016](https://www.youtube.com/playlist?list=PLwB4Uz_0hoVOLU7LPRNL4lAmJeAv7HQ-b)
* [Max Bucknell Magento 2 Javascript](https://www.youtube.com/watch?v=tHxebA-jOSo)
* [Max Pronko DevChannel](https://www.youtube.com/channel/UCxbWGz6h6KNQsi2ughRUV2Q)
* [The Magento 2 Beginner Tutorial Class](https://www.youtube.com/playlist?list=PLtaXuX0nEZk9eL59JGE3ny-_GAU-z5X5D\&utm_content=buffer797bf\&utm_medium=social\&utm_source=twitter.com\&utm_campaign=buffer) - Free YouTube Series for learning Magento 2.
* [Vinai Kopp Mage2Katas](https://www.youtube.com/channel/UCRFDWo7jTlrpEsJxzc7WyPw)
* [Mage2.tv](https://www.mage2.tv) - Magento 2 Developer Screencasts by Vinai Kopp
* [Yireo Training](https://www.yireo.com/training) - Various Magento 2 courses for backend and frontend development

***

## Platforms

* [StackExchange](http://magento.stackexchange.com/) - Q/A Forum.

***

## Official Resources

* [Magento Github Repository](https://github.com/magento/magento2) ⭐ 12,040 | 🐛 1,977 | 🌐 PHP | 📅 2026-02-12 - Github Repository.

* [Magento Coding Standards](https://github.com/magento/magento-coding-standard) ⭐ 371 | 🐛 95 | 🌐 PHP | 📅 2025-12-19 - Official Magento2 Advanced Set of
  Rules for PHP\_CodeSniffer.

* [Magento 2 data migration tool](https://github.com/magento/data-migration-tool) ⭐ 339 | 🐛 123 | 🌐 PHP | 📅 2025-06-03 - Official Magento 1 to Magento 2 migration tool.

* [Magento 2 Architecture](https://github.com/magento/architecture) ⭐ 279 | 🐛 66 | 📅 2025-01-21 - A place where Magento architectural discussions
  happen.

* [Magento Official Website](https://www.magento.com) - Magento's official Website.

* [Magento Developer Documentation](http://devdocs.magento.com/) - Official Developer Documentation.

* [Magento Forum](https://community.magento.com/) - Community Forum by Magento.

* [Magento Developer Blog](https://community.magento.com/t5/Magento-DevBlog/bg-p/devblog?nobounce=) - Developer Blog by
  Magento.

* Magento Masters 2017
  * [Peter Jaap Blaakmeer](https://twitter.com/PeterJaap) - CTO at [elgentos](https://www.elgentos.nl/)
  * Carmen Bremen - Freelancer at [neoshops](http://neoshops.de/)
  * Tony Brown - Technical Director at [space48](http://www.space48.com/)
  * Hirokazu Nishi
  * Brent Peterson
  * Sonja Riesterer
  * Kristof Ringleff
  * Alessandro Ronchi
  * Matthias Zeis
  * Kuba Zwolinski
  * Gabriel Guarino
  * Phillip Jackson
  * Sander Mangel
  * Raphael Petrini
  * Fabian Schmengler
  * Marius Strajeru
  * Anna Völkl
  * Ivan Chepurnyi
  * Vinai Kopp
  * Jisse Reitsma

***

## List of trustworthy Extension Developers

* [Aheadworks](https://www.aheadworks.com/)
* [Altima](https://shop.altima.net.au/)
* [Blue Jalappeno](http://bluejalappeno.com/)
* [CustomGento](https://www.customgento.com/extensions/)
* [Dotmailer](https://www.dotmailer.com/)
* [Integer-net](https://www.integer-net.com/solr-magento/)
* [Genmato](https://genmato.com/)
* [Fooman](http://store.fooman.co.nz/)
* [Ebizmarts](https://ebizmarts.com/)
* [Magemail](https://magemail.co/)
* [MagePal](https://packagist.org/packages/magepal/)
* [Modulwerft](https://www.modulwerft.com/)
* [Paradox Labs](https://www.paradoxlabs.com/)
* [The Extension Lab](https://github.com/theextensionlab/)
* [Sweet Tooth](https://www.sweettoothrewards.com/)
* [Rocket Web](http://rocketweb.com/)
* [ProxiBlue](https://www.proxiblue.com.au/)
* [Unirgy](http://www.unirgy.com/)
* [WebShopApps](http://webshopapps.com/eu/)
* [Yireo](https://www.yireo.com/)
* [FireBear Studio](https://firebearstudio.com/)

> **Magento Extension Developers Network (ExtDN)**
> The Magento Extension Developers Network (ExtDN) is a vetted network of extension developers whose core business is to
> develop and sell quality Magento extensions. I founded ExtDN to bring accountability and trust to the Magento extension
> market. ExtDN members agree to hold themselves accountable to high standards of coding, copyright and business conduct.

Explanation
by [Fooman](http://store.fooman.co.nz/blog/how-to-find-trustworthy-information-about-magento-extensions.html)

***

## Other Magento 2 related Awesome Lists

* [Awesome PHP](https://github.com/ziadoz/awesome-php) ⭐ 32,365 | 🐛 68 | 📅 2026-01-17 - A curated List of Awesome PHP Resources.
* [Mageres](https://github.com/aleron75/mageres) ⭐ 1,008 | 🐛 3 | 🌐 PHP | 📅 2026-02-09 - Alessandro Ronchi's List of resources for Magento 1 and Magento 2.
* [Awesome Magento](https://github.com/sunel/awesome-magento) ⭐ 89 | 🐛 0 | 📅 2021-07-06 - An Awesome Magento List with mixed M1 and M2 Content
  by [sunel](https://github.com/sunel).

***

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, David Lambauer has waived all copyright and related or neighboring rights to this
work.

***

Thanks [Anna Völkl](https://github.com/avoelkl) & [Sander Mangel](https://github.com/sandermangel) for collecting all
the language packs!

***

Thanks [MageTitans](http://www.magetitans.co.uk/) for sharing the Talks on YouTube.
