---
title: setMeteredKey
type: docs
weight: 40
url: /php-java/metered/setmeteredkey/
---

# setMeteredKey(java.lang.String, java.lang.String) method
Sets metered public and private key.
 If you purchase metered license, when start application, this API should be called, normally, this is enough.
 However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status,
 to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

##  Parameters

| name | description |
| --- | --- |
| publicKey | public key |
| privateKey | private key |


