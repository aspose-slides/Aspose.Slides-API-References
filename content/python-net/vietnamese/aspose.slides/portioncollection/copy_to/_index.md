---
title: copy_to method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Copies the elements of the **System.Collections.Generic.ICollection`1** to an **System.Array**, starting at a particular **System.Array** index.

```python
def copy_to(self, array, array_index):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| array | **List[IPortion]** | Mảng một chiều **System.Array** là đích của các phần tử được sao chép từ **System.Collections.Generic.ICollection`1**. **System.Array** phải có chỉ mục bắt đầu từ 0. |
| array_index | **int** | Chỉ mục bắt đầu từ 0 trong `array` nơi việc sao chép bắt đầu. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` nhỏ hơn 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Số phần tử trong nguồn **System.Collections.Generic.ICollection`1** lớn hơn không gian khả dụng từ `array_index` đến cuối `array` đích. |

### Xem thêm
* lớp [`PortionCollection`](/slides/python-net/vi/aspose.slides/portioncollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)