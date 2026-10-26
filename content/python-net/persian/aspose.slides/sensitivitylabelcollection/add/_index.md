---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
یک SensitivityLabel را به مجموعه اضافه می‌کند.

### بازگرداندن

نمایه‌ای که SensitivityLabel در آن اضافه شده است.



```python
def add(self, label):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/fa/aspose.slides/isensitivitylabel) | شیء SensitivityLabel که در انتهای مجموعه اضافه می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی که برچسب حساسیتی با همان Id قبلاً اضافه شده باشد، رخ می‌دهد. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/fa/aspose.slides/sensitivitylabelassignmenttype) |  |



### موارد مرتبط
* کلاس [`ISensitivityLabel`](/slides/python-net/fa/aspose.slides/isensitivitylabel)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/fa/aspose.slides/sensitivitylabelassignmenttype)
* کلاس [`SensitivityLabelCollection`](/slides/python-net/fa/aspose.slides/sensitivitylabelcollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)