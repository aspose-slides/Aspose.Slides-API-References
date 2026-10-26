---
title: add method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Dodaje SensitivityLabel do kolekcji.

### Zwraca

Indeks, pod którym SensitivityLabel został dodany.



```python
def add(self, label):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/pl/aspose.slides/isensitivitylabel) | Obiekt SensitivityLabel, który ma zostać dodany na koniec kolekcji. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucony, gdy etykieta poufności o tym samym Id została już dodana. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/pl/aspose.slides/sensitivitylabelassignmenttype) |  |



### Zobacz także
* klasa [`ISensitivityLabel`](/slides/python-net/pl/aspose.slides/isensitivitylabel)
* enumeracja [`SensitivityLabelAssignmentType`](/slides/python-net/pl/aspose.slides/sensitivitylabelassignmenttype)
* klasa [`SensitivityLabelCollection`](/slides/python-net/pl/aspose.slides/sensitivitylabelcollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)