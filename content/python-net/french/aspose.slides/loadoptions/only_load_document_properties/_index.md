---
title: only_load_document_properties property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties propriété
Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe.
            La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré.
            La valeur false signifie que la présentation chiffrée entière doit être chargée en utilisant le bon mot de passe.
            Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée.
            Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée.
            Lecture/écriture **bool**.

### Définition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Voir aussi
* classe [`LoadOptions`](/slides/python-net/fr/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)