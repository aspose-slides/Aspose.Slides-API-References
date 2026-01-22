---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/isensitivitylabelcollection/add/
weight: 10
---


## add {#isensitivitylabel}
Adds a SensitivityLabel to the collection.

### Returns

The index at which the SensitivityLabel was added.



```python
def add(self, label):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/aspose.slides/isensitivitylabel) | The SensitivityLabel object to be added at the end of the collection. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when the sensitivity label with the same Id has already been added. |


## add {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/aspose.slides/sensitivitylabelassignmenttype) |  |



### See Also
* class [`ISensitivityLabel`](/slides/python-net/aspose.slides/isensitivitylabel)
* class [`ISensitivityLabelCollection`](/slides/python-net/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/aspose.slides/sensitivitylabelassignmenttype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

