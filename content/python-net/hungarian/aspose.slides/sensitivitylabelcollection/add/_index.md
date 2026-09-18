---
title: add method
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Hozzáad egy SensitivityLabel-t a gyűjteményhez.

### Visszatér

Az az index, ahol a SensitivityLabel hozzá lett adva.



```python
def add(self, label):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/hu/aspose.slides/isensitivitylabel) | A SensitivityLabel objektum, amelyet a gyűjtemény végére kell hozzáadni. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Akkor kerül kivételre, ha már hozzá lett adva ugyanazzal az Id-vel rendelkező érzékenységi címke. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/hu/aspose.slides/sensitivitylabelassignmenttype) |  |



### Lásd még
* osztály [`ISensitivityLabel`](/slides/python-net/hu/aspose.slides/isensitivitylabel)
* enumeráció [`SensitivityLabelAssignmentType`](/slides/python-net/hu/aspose.slides/sensitivitylabelassignmenttype)
* osztály [`SensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/sensitivitylabelcollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)