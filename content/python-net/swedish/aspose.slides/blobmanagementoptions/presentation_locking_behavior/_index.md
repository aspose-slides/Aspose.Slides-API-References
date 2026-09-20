---
title: presentation_locking_behavior property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior egenskap
Denna egenskap definierar om en instans av Presentation-klassen kan vara en ägare av källan - fil 
            eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper 
            till att förbättra minnesanvändning och prestanda när du arbetar med BLOBs, men källan (ström eller fil) 
            kan inte ändras under Presentation-instansens livstid.

### Definition:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Se även
* klass [`BlobManagementOptions`](/slides/python-net/sv/aspose.slides/blobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)