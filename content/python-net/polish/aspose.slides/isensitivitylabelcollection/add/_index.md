---
title: add method
second_title: Odwołanie do API Aspose.Slides dla Pythona poprzez .NET
description: 
type: docs
url: /pl/aspose.slides/isensitivitylabelcollection/add/
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
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy etykieta poufności o tym samym Id została już dodana. |


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
* class [`ISensitivityLabel`](/slides/python-net/pl/aspose.slides/isensitivitylabel)
* class [`ISensitivityLabelCollection`](/slides/python-net/pl/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/pl/aspose.slides/sensitivitylabelassignmenttype)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)