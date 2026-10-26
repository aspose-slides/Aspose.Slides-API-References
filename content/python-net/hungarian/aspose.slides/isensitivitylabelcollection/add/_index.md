---
title: add method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Hozzáad egy SensitivityLabel-t a gyűjteményhez.

### Returns
Az index, amelynél a SensitivityLabel hozzá lett adva.



```python
def add(self, label):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/hu/aspose.slides/isensitivitylabel) | A SensitivityLabel objektum, amelyet a gyűjtemény végére kell hozzáadni. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Aktív, ugyanazzal az Id-vel rendelkező érzékenységi címke már hozzá lett adva. |


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



### See Also
* osztály [`ISensitivityLabel`](/slides/python-net/hu/aspose.slides/isensitivitylabel)
* osztály [`ISensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/isensitivitylabelcollection)
* felsorolás [`SensitivityLabelAssignmentType`](/slides/python-net/hu/aspose.slides/sensitivitylabelassignmenttype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)