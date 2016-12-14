# Magento 2 Mobile detect system

Magento 2 Mobile detect system can be used to load diffrent themses base on the client device (desktop, table mobile).
It uses the library https://github.com/serbanghita/Mobile-Detect.

# How to use the module

The main configuraton can be done under the Content > Design > Configuration. There (Design Rule > User Agent Rules) you can add user agent expressions.

* add "eadesign_is_mobile" to load a theme for mobile
* add "eadesign_is_tablet" to load a theme for tablet
* add "eadesign_is_desktop" to load a theme for desktop

Under system configurations you need to enable the extension. Also there you will find 3 fields for redirects. 
If you add a url to the mobile field for example the user will be redirected to the url in there. 
This can be usefull if you want ot use a diffrent website/store view url for the mobile theme.


# Installation. 

You can install the module via composer or manually by adding it to the app/code directory. The module is available on packagist.org

Via composer

- composer config repositories.magento2-mobiledetect git git@github.com:EaDesgin/magento2-warehouses;
- sudo composer require eadesignro/module-mobiledetect;
- php bin/magento setup:upgrade;

# Uninstall 

You need to remove the module. 