---
title: set_license method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ilicense/set_license/
weight: 30
---


## set_license {#string}
Licenses the component.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | string | Can be a full or short file name or name of an embedded resource.<br/><br/>            Use an empty string to switch to evaluation mode. |

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



## set_license {#systemiostream}
Licenses the component.


```python
def set_license(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream |  |

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



