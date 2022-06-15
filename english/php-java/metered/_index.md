---
title: Metered
type: docs
weight: 0
url: /php-java/metered/
---

# Metered class
Provides methods to set metered key.

## Constructors

| name | description |
| --- | --- |
| [Metered](/slides/php-java/metered/metered/)() | Initializes a new instance of this class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getConsumptionCredit](/slides/php-java/metered/getconsumptioncredit/)() | double | Gets consumption credit |
| [getConsumptionQuantity](/slides/php-java/metered/getconsumptionquantity/)() | double | Gets consumption file size |
| [setMeteredKey](/slides/php-java/metered/setmeteredkey/)(String, String) | void | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
