---
title: set_license method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/license/set_license/
weight: 40
---


## set_license {#str}
Licenses the component.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | **str** | Can be a full or short file name or name of an embedded resource.<br/><br/>            Use an empty string to switch to evaluation mode. |

### Examples

In this example, an attempt will be made to find a license file named MyLicense.lic
            in the folder that contains the component, in the folder that contains the calling assembly,
            in the folder of the entry assembly and then in the embedded resources of the calling assembly.

### Remarks

Tries to find the license in the following locations:


1. Explicit path.


2. The folder of the component assembly.


3. The folder of the client's calling assembly.


4. The folder of the entry assembly.


5. An embedded resource in the client's calling assembly.


**Note:** On the .NET Compact Framework, tries to find the license only in these locations:


1. Explicit path.


2. An embedded resource in the client's calling assembly.


## set_license {#iorawiobase}
Licenses the component.


```python
def set_license(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | A stream that contains the license. |

### Remarks

Use this method to load a license from a stream.



### See Also
* class [`License`](/slides/python-net/aspose.slides/license)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

