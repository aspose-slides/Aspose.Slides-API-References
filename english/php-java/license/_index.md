---
title: License
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/license/
---

## License class
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

| Name | Description |
| --- | --- |
| [License](license)() | Initializes a new instance of this class. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |

## Methods

| Name | Description |
| --- | --- |
| [getVersion](getversion)() | Returns version of Aspose.Slides for Java. |
| [isLicensed](islicensed)() |  |
| [resetLicense](resetlicense)() | Reset the license Use this method to reset license in component License license = new License(); license.resetLicense(); |
| [setLicense](setlicense)(InputStream) | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |
| [setLicense](setlicense)(String) | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |
