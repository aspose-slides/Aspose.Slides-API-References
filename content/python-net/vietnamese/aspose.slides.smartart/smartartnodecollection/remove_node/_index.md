---
title: remove_node method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Xóa nút hoặc nút con theo chỉ mục


```python
def remove_node(self, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 của nút |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | chỉ mục nhỏ hơn 0. -hoặc- chỉ mục bằng hoặc lớn hơn số lượng nút anh em |


## remove_node(self, node) {#ismartartnode}
Xóa nút hoặc nút con


```python
def remove_node(self, node):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/vi/aspose.slides.smartart/ismartartnode) | Nút cần xóa |



### Xem Thêm
* lớp [`ISmartArtNode`](/slides/python-net/vi/aspose.slides.smartart/ismartartnode)
* lớp [`SmartArtNodeCollection`](/slides/python-net/vi/aspose.slides.smartart/smartartnodecollection)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)