---
title: add method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Ajoute un SensitivityLabel à la collection.

### Valeur de retour

L'index auquel le SensitivityLabel a été ajouté.



```python
def add(self, label):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/fr/aspose.slides/isensitivitylabel) | L'objet SensitivityLabel à ajouter à la fin de la collection. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée lorsque le label de sensibilité avec le même Id a déjà été ajouté. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/fr/aspose.slides/sensitivitylabelassignmenttype) |  |



### Voir aussi
* classe [`ISensitivityLabel`](/slides/python-net/fr/aspose.slides/isensitivitylabel)
* énumération [`SensitivityLabelAssignmentType`](/slides/python-net/fr/aspose.slides/sensitivitylabelassignmenttype)
* classe [`SensitivityLabelCollection`](/slides/python-net/fr/aspose.slides/sensitivitylabelcollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)