---
title: License
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/license/
---

## License class
Provides methods to license the component.
 
 In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
 
 
### License {#License}

| Name | Description |
| --- | --- |
| License() | Initializes a new instance of this class. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |

 **Returns:**
License


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () | Returns version of Aspose.Slides for Java. |

 **Returns:**
String


---


### isLicensed {#isLicensed}

| Name | Description |
| --- | --- |
| isLicensed () |  |

 **Returns:**
boolean


---


### resetLicense {#resetLicense}

| Name | Description |
| --- | --- |
| resetLicense () | Reset the license. Use this function to reset license in component. |


---


### setLicenseFromStream  {#setLicenseFromStream }

| Name | Description |
| --- | --- |
| setLicenseFromStream  (License, ReadStream, Function) | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| license | License  | link to self |
| stream | ReadStream | A stream that contains the license. Use null to switch to evaluation mode. |
| callback | Function | callback(error, Returns) - Callback to be called when the method has completed |


---


### setLicense {#setLicense}

| Name | Description |
| --- | --- |
| setLicense (String) | Licenses the component. In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| namePath | String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |


---


