---
title: setLicense
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/license/setlicense/
---

## setLicense(InputStream stream)  method
Licenses the component.
 
 In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
 

```php
$license = new License();
$license->setLicense("MyLicense.lic");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | A stream that contains the license. Use null to switch to evaluation mode. |

### Returns
void


---


## setLicense(String namePath)  method
Licenses the component.
 
 In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
 

```php
$license = new License();
$license->setLicense("MyLicense.lic");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| namePath | String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |

### Returns
void


---


