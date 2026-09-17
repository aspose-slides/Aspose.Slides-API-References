---
title: add method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
يضيف SensitivityLabel إلى المجموعة.

### القيمة المرجعة

الفهرس الذي تم إضافة SensitivityLabel إليه.



```python
def add(self, label):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ar/aspose.slides/isensitivitylabel) | كائن SensitivityLabel ليُضاف في نهاية المجموعة. |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح عندما تكون SensitivityLabel ذات Id نفسها قد أضيفت بالفعل. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ar/aspose.slides/sensitivitylabelassignmenttype) |  |



### انظر أيضًا
* الفئة [`ISensitivityLabel`](/slides/python-net/ar/aspose.slides/isensitivitylabel)
* التعداد [`SensitivityLabelAssignmentType`](/slides/python-net/ar/aspose.slides/sensitivitylabelassignmenttype)
* الفئة [`SensitivityLabelCollection`](/slides/python-net/ar/aspose.slides/sensitivitylabelcollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)