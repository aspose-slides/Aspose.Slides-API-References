---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects propriété
Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.

Les types des objets binaires incorporés :

* Projet VBA [`IPresentation.vba_project`](/slides/python-net/fr/aspose.slides/ipresentation/vba_project)
* Données incorporées d'objet OLE [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* Données binaires de contrôle ActiveX [`IControl.active_x_control_binary`](/slides/python-net/fr/aspose.slides/icontrol/active_x_control_binary)

Lecture/écriture **bool**.

### Remarques

Par défaut est **false** .

### Définition:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Voir aussi
* classe [`ILoadOptions`](/slides/python-net/fr/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)