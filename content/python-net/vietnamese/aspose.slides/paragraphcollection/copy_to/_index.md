---
title: copy_to method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Sao chép các phần tử của **System.Collections.Generic.ICollection`1** vào một **System.Array**, bắt đầu tại một chỉ mục **System.Array** cụ thể.


```python
def copy_to(self, array, array_index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| array | **List[IParagraph]** | **System.Array** một chiều là nơi đích của các phần tử được sao chép từ **System.Collections.Generic.ICollection`1**. **System.Array** phải có chỉ mục bắt đầu từ 0. |
| array_index | **int** | Chỉ mục bắt đầu từ 0 trong `array` nơi việc sao chép bắt đầu. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` nhỏ hơn 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Số phần tử trong **System.Collections.Generic.ICollection`1** nguồn lớn hơn không gian có sẵn từ `array_index` đến cuối `array` đích. |



### Xem thêm
* lớp [`ParagraphCollection`](/slides/python-net/vi/aspose.slides/paragraphcollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)