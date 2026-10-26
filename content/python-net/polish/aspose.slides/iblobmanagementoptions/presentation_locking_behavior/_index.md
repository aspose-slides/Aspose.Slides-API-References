---
title: presentation_locking_behavior property
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior właściwość
This property defines if an instance of the Presentation class can be an owner of the source - file 
            or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps 
            to improve memory consumption and performance while working with BLOBs, but the source (stream or file) 
            can't be changed during Presentation's instance lifetime. This is an example:

### Definicja:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Zobacz także
* klasa [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)