---
title: add method
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Aggiunge un SensitivityLabel alla collezione.

### Restituisce

L'indice al quale è stato aggiunto il SensitivityLabel.



```python
def add(self, label):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/it/aspose.slides/isensitivitylabel) | L'oggetto SensitivityLabel da aggiungere alla fine della collezione. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando l'etichetta di sensibilità con lo stesso Id è già stata aggiunta. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/it/aspose.slides/sensitivitylabelassignmenttype) |  |



### Vedi anche
* classe [`ISensitivityLabel`](/slides/python-net/it/aspose.slides/isensitivitylabel)
* classe [`ISensitivityLabelCollection`](/slides/python-net/it/aspose.slides/isensitivitylabelcollection)
* enumerazione [`SensitivityLabelAssignmentType`](/slides/python-net/it/aspose.slides/sensitivitylabelassignmenttype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)