---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Lägger till en SensitivityLabel i samlingen.

### Returnvärde
Indexet där SensitivityLabel lades till.



```python
def add(self, label):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/sv/aspose.slides/isensitivitylabel) | SensitivityLabel-objektet som ska läggas till i slutet av samlingen. |

### Undantag
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när en sensitivitetsetikett med samma Id redan har lagts till. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/sv/aspose.slides/sensitivitylabelassignmenttype) |  |



### Se även
* klass [`ISensitivityLabel`](/slides/python-net/sv/aspose.slides/isensitivitylabel)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/sv/aspose.slides/sensitivitylabelassignmenttype)
* klass [`SensitivityLabelCollection`](/slides/python-net/sv/aspose.slides/sensitivitylabelcollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)