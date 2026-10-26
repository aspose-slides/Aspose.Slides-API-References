---
title: add method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
يضيف SensitivityLabel إلى المجموعة.

### Returns
القيمة المعادة

الفهرس الذي تم إضافة SensitivityLabel فيه.


```python
def add(self, label):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ar/aspose.slides/isensitivitylabel) | كائن SensitivityLabel ليتم إضافته في نهاية المجموعة. |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُرفع عندما يكون تم إضافة ملصق الحساسية الذي له نفس Id مسبقاً. |


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
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ar/aspose.slides/sensitivitylabelassignmenttype) |  |

### See Also
* class [`ISensitivityLabel`](/slides/python-net/ar/aspose.slides/isensitivitylabel)
* class [`ISensitivityLabelCollection`](/slides/python-net/ar/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/ar/aspose.slides/sensitivitylabelassignmenttype)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)