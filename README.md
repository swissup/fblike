# Fblike

It's a metapackage for the [source code repository](https://github.com/swissup/module-fblike).

#### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/fblike --prefer-source
bin/magento module:enable Swissup_Core Swissup_Fblike
bin/magento setup:upgrade
```
