---
title: presentation_locking_behavior property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior Eigenschaft
Diese Eigenschaft definiert, ob eine Instanz der Presentation Klasse Eigentümer der Quelle – Datei
            oder des Streams während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies trägt dazu bei,
            den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei)
            kann während der Lebensdauer der Presentation-Instanz nicht geändert werden.

### Definition:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Siehe auch
* Klasse [`BlobManagementOptions`](/slides/python-net/de/aspose.slides/blobmanagementoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)