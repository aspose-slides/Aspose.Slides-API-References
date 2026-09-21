---
title: presentation_locking_behavior property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior eigenschap
Deze eigenschap bepaalt of een instantie van de Presentation klasse eigenaar kan zijn van de bron- bestand of stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren bij het werken met BLOB’s, maar de bron (stream of bestand) kan niet worden gewijzigd tijdens de levensduur van de Presentation-instantie. Dit is een voorbeeld:

### Definitie:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Zie ook
* klasse [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)