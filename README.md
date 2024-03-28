# ![image logo](./docs/favicon.svg) WindAndKite_PageBuilderCoreWebVitals

A Magento 2 Module introducing additional attributes to improve PageBuilder Elements CWV

## Why is it needed
Magento Core Page Builder elements don't allow for the configuration of all attributes that are recommended to use for
improving Core Web Vitals. This module aims to customise the existing Page Builder elements in order to give that
control to the admin users.

## What Customisations are Added
- Image:
  - Loading attribute:
    - Gives admin users the ability to choose between Eager or Lazy loading for Desktop and mobile image independently
  - Height/Width:
    - Gives admin users the ability to set a static Height and Width Value for Desktop and mobile image independently

## Installation

The package is available via packagist for easy installation via composer

Install via composer:

```BASH
composer require windandkite/module-page-builder-core-web-vitals
```

```BASH
bin/magento module:enable WindAndKite_PageBuilderCoreWebVitals
```

## Setup
This module requires no setup configuration.

## Contributions
to contribute to this project please install the package with the `--prefer-source` flag to download the Git source, any
changes should then be pushed to GitHub and follow the usual Code Review Process. Once reviewed and merged in please
create a release and appropriate tag for the changes ensuring to follow Semver.
