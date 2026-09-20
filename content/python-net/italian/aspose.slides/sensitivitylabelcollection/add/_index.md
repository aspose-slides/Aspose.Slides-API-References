---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Aggiunge un SensitivityLabel alla raccolta.

### Returns

L'indice al quale il SensitivityLabel è stato aggiunto.



```python
def add(self, label):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/it/aspose.slides/isensitivitylabel) | L'oggetto SensitivityLabel da aggiungere alla fine della raccolta. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando il sensitivity label con lo stesso Id è già stato aggiunto. |


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
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/it/aspose.slides/sensitivitylabelassignmenttype) |  |



### See Also
* class [`ISensitivityLabel`](/slides/python-net/it/aspose.slides/isensitivitylabel)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/it/aspose.slides/sensitivitylabelassignmenttype)
* class [`SensitivityLabelCollection`](/slides/python-net/it/aspose.slides/sensitivitylabelcollection)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)