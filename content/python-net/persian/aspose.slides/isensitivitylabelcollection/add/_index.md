---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
یک SensitivityLabel را به مجموعه اضافه می‌کند.

### Returns

اندیسی که SensitivityLabel در آن اضافه شده است.



```python
def add(self, label):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/fa/aspose.slides/isensitivitylabel) | شیء SensitivityLabel برای اضافه شدن در پایان مجموعه. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | زمانی که برچسب حساسیت با همان Id قبلاً اضافه شده باشد، پرتاب می‌شود. |


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
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/fa/aspose.slides/sensitivitylabelassignmenttype) |  |



### See Also
* کلاس [`ISensitivityLabel`](/slides/python-net/fa/aspose.slides/isensitivitylabel)
* کلاس [`ISensitivityLabelCollection`](/slides/python-net/fa/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/fa/aspose.slides/sensitivitylabelassignmenttype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)