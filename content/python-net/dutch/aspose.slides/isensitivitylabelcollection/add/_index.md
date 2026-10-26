---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Voegt een SensitivityLabel toe aan de collectie.

### Retour

De index waarop het SensitivityLabel is toegevoegd.



```python
def add(self, label):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/nl/aspose.slides/isensitivitylabel) | Het SensitivityLabel-object dat aan het einde van de collectie moet worden toegevoegd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer het gevoeligheidslabel met dezelfde Id al is toegevoegd. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/nl/aspose.slides/sensitivitylabelassignmenttype) |  |



### Zie ook
* klasse [`ISensitivityLabel`](/slides/python-net/nl/aspose.slides/isensitivitylabel)
* klasse [`ISensitivityLabelCollection`](/slides/python-net/nl/aspose.slides/isensitivitylabelcollection)
* enumeratie [`SensitivityLabelAssignmentType`](/slides/python-net/nl/aspose.slides/sensitivitylabelassignmenttype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)