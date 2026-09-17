---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded propriété
Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe et que les propriétés du document de ce fichier sont publiques.
La valeur true signifie que seules les propriétés du document sont chargées à partir d’un fichier de présentation chiffré sans utilisation du mot de passe.
La valeur false signifie que l’ensemble de la présentation chiffrée est chargé avec le bon mot de passe, pas uniquement les propriétés du document.
Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours false.
Si les propriétés du document d’un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false.
Si Presentation.EncryptDocumentProperties est true alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false.
Lecture seule **bool**.

### Définition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Voir aussi
* classe [`ProtectionManager`](/slides/python-net/fr/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)