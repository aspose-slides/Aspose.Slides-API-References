---
title: presentation_locking_behavior property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior propriété
Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier 
            ou le flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide 
            à améliorer la consommation de mémoire et les performances lors du travail avec les BLOBs, mais la source (flux ou fichier) 
            ne peut pas être modifiée pendant la durée de vie de l'instance de Presentation. Voici un exemple:

### Définition:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Voir aussi
* classe [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)