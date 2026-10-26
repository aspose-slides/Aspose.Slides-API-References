---
title: add method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Thêm một SensitivityLabel vào bộ sưu tập.

### Trả về

Chỉ mục mà SensitivityLabel đã được thêm vào.



```python
def add(self, label):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/vi/aspose.slides/isensitivitylabel) | Đối tượng SensitivityLabel sẽ được thêm vào cuối bộ sưu tập. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi nhãn nhạy cảm có cùng Id đã được thêm trước đó. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/vi/aspose.slides/sensitivitylabelassignmenttype) |  |



### Xem Thêm
* lớp [`ISensitivityLabel`](/slides/python-net/vi/aspose.slides/isensitivitylabel)
* liệt kê [`SensitivityLabelAssignmentType`](/slides/python-net/vi/aspose.slides/sensitivitylabelassignmenttype)
* lớp [`SensitivityLabelCollection`](/slides/python-net/vi/aspose.slides/sensitivitylabelcollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)