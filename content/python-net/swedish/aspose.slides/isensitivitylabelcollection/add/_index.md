---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Adds a SensitivityLabel to the collection.

### Returnerar

Indexet där SensitivityLabel lades till.



```python
def add(self, label):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/sv/aspose.slides/isensitivitylabel) | SensitivityLabel-objektet som ska läggas till i slutet av samlingen. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när sensitivity label med samma Id redan har lagts till. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/sv/aspose.slides/sensitivitylabelassignmenttype) |  |



### Se även
* klass [`ISensitivityLabel`](/slides/python-net/sv/aspose.slides/isensitivitylabel)
* klass [`ISensitivityLabelCollection`](/slides/python-net/sv/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/sv/aspose.slides/sensitivitylabelassignmenttype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)