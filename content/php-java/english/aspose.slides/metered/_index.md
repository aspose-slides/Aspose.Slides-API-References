---
title: Metered
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/metered/
---

## Metered class
Provides methods to set metered key.
### Metered {#Metered}

| Name | Description |
| --- | --- |
| Metered() | Initializes a new instance of this class. |

 **Returns:**
Metered


---


### getConsumptionCredit {#getConsumptionCredit}

| Name | Description |
| --- | --- |
| getConsumptionCredit () | Gets consumption credit |

 **Returns:**
double


---


### getConsumptionQuantity {#getConsumptionQuantity}

| Name | Description |
| --- | --- |
| getConsumptionQuantity () | Gets consumption file size |

 **Returns:**
double


---


### setMeteredKey {#setMeteredKey}

| Name | Description |
| --- | --- |
| setMeteredKey (String, String) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| publicKey | String | public key |
| privateKey | String | private key |

 **Returns:**
void


---


