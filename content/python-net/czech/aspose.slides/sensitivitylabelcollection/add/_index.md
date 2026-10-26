---
title: add method
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Přidá objekt SensitivityLabel do kolekce.

### Návratová hodnota

Index, na kterém byl objekt SensitivityLabel přidán.



```python
def add(self, label):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/cs/aspose.slides/isensitivitylabel) | Objekt SensitivityLabel, který má být přidán na konci kolekce. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud byl štítek citlivosti se stejným Id již přidán. |


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
* výčet [`SensitivityLabelAssignmentType`](/slides/python-net/cs/aspose.slides/sensitivitylabelassignmenttype)
* třída [`SensitivityLabelCollection`](/slides/python-net/cs/aspose.slides/sensitivitylabelcollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)