---
title: presentation_locking_behavior property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior propriété
Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier 
            ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide 
            à améliorer la consommation de mémoire et les performances lors du traitement des BLOB, mais la source (flux ou fichier) 
            ne peut pas être modifiée pendant la durée de vie de l'instance Presentation.

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
* classe [`BlobManagementOptions`](/slides/python-net/fr/aspose.slides/blobmanagementoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)