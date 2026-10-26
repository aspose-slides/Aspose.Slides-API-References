---
title: add method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Přidá SensitivityLabel do kolekce.

### Návratová hodnota

Index, na kterém byl SensitivityLabel přidán.



```python
def add(self, label):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/cs/aspose.slides/isensitivitylabel) | Objekt SensitivityLabel, který bude přidán na konec kolekce. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když již byl přidán štítek citlivosti se stejným Id. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/cs/aspose.slides/sensitivitylabelassignmenttype) |  |



### Viz také
* třída [`ISensitivityLabel`](/slides/python-net/cs/aspose.slides/isensitivitylabel)
* třída [`ISensitivityLabelCollection`](/slides/python-net/cs/aspose.slides/isensitivitylabelcollection)
* výčet [`SensitivityLabelAssignmentType`](/slides/python-net/cs/aspose.slides/sensitivitylabelassignmenttype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)