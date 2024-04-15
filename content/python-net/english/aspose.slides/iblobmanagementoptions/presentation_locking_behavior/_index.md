---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---


## presentation_locking_behavior property
This property defines if an instance of the Presentation class can be an owner of the source - file 
            or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps 
            to improve memory consumption and performance while working with BLOBs, but the source (stream or file) 
            can't be changed during Presentation's instance lifetime. This is an example:

### Definition:
```python
@property
def presentation_locking_behavior(self):
    ...
@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### See Also
* class [`IBlobManagementOptions`](/slides/python-net/aspose.slides/iblobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
