# Magento 2 Custom Shipping Method

This module provide a custom shipping method on the site.

## Features
* Option to Enabled and Disabled Module
* Changing Title
* Changing Method Name
* Dyanmic Price
* Calculate Handlikng Fee
* Display Error Message
* Ship to Applicable Countries
* Ship to Specific Countries
* Show Method if Not Applicable
* Sort Order

## Installation

Copy the content of the repo to the app/code/Zone/ShippingMethod/ folder

Enable module:
```
php bin/magento module:enable Zone_ShippingMethod
```

Disable module: (Optional)
```
php bin/magento module:disable Zone_ShippingMethod --clear-static-content
```

Update system:
```
php bin/magento setup:upgrade
php bin/magento cache:flush
php bin/magento cache:clean
```
## Author

* **Zekinah Lecaros** - *Initial work* - [Zekinah Lecaros](https://github.com/zekinah)

## License

[MIT](http://opensource.org/licenses/MIT)
