---
title: License
type: docs
weight: 0
url: /php-java/license/
---

# License class
Provides methods to license the component.
 
 In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
 
 

```php
  $example;
  $an;
  $be;
  $find;
  $file;
  $in;
  $that;
  $component;
  $in;
  $that;
  $calling;
  $in;
  $of;
  $assembly;
  $in;
  $resources;
  $calling;
  $assembly = $$missing$;
```

## Constructors

| name | description |
| --- | --- |
| [License](/slides/php-java/license/license/)() | Initializes a new instance of this class. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getVersion](/slides/php-java/license/getversion/)() | String | Returns version of Aspose.Slides for Java. |
| [isLicensed](/slides/php-java/license/islicensed/)() | boolean |  |
| [resetLicense](/slides/php-java/license/resetlicense/)() | void | Reset the license Use this method to reset license in component License license = new License(); license.resetLicense(); |
| [setLicense](/slides/php-java/license/setlicense/)(InputStream) | void | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |
| [setLicense](/slides/php-java/license/setlicense/)(String) | void | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |
