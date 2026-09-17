---
title: add method
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Fügt der Sammlung ein SensitivityLabel hinzu.

### Rückgabewert

Der Index, an dem das SensitivityLabel hinzugefügt wurde.



```python
def add(self, label):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/de/aspose.slides/isensitivitylabel) | Das SensitivityLabel-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn das SensitivityLabel mit derselben Id bereits hinzugefügt wurde. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/de/aspose.slides/sensitivitylabelassignmenttype) |  |



### Siehe auch
* Klasse [`ISensitivityLabel`](/slides/python-net/de/aspose.slides/isensitivitylabel)
* Klasse [`ISensitivityLabelCollection`](/slides/python-net/de/aspose.slides/isensitivitylabelcollection)
* Aufzählung [`SensitivityLabelAssignmentType`](/slides/python-net/de/aspose.slides/sensitivitylabelassignmenttype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)