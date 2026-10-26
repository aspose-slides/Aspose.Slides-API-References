---
title: copy_to method
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Sao chép các phần tử của **System.Collections.Generic.ICollection`1** vào một **System.Array**, bắt đầu tại một chỉ mục **System.Array** cụ thể.

```python
def copy_to(self, array, array_index):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| array | **List[IBehavior]** | **System.Array** một chiều là đích của các phần tử được sao chép từ **System.Collections.Generic.ICollection`1**. **System.Array** phải có chỉ mục bắt đầu từ 0. |
| array_index | **int** | Chỉ mục bắt đầu từ 0 trong `array` mà tại đó việc sao chép bắt đầu. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` nhỏ hơn 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Số phần tử trong **System.Collections.Generic.ICollection`1** nguồn lớn hơn không gian khả dụng từ `array_index` tới cuối `array` đích. |

### Xem thêm
* lớp [`BehaviorCollection`](/slides/python-net/vi/aspose.slides.animation/behaviorcollection)
* module [`aspose.slides.animation`](/slides/python-net/vi/aspose.slides.animation)
* thư viện [`Aspose.Slides`](/slides/python-net)