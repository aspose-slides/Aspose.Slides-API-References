---
title: presentation_locking_behavior property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior egenskap
Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan - fil eller ström under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesanvändning och prestanda vid arbete med BLOBs, men källan (ström eller fil) kan inte ändras under Presentation-instansens livstid. Detta är ett exempel:

### Definition:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Se också
* klass [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)