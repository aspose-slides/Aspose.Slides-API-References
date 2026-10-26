---
title: remove_node method
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Xóa nút hoặc nút con theo chỉ mục.


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | chỉ mục nhỏ hơn 0.  -or- chỉ mục bằng hoặc lớn hơn số lượng nút anh em. |


## remove_node(self, node_obj) {#ismartartnode}
Xóa nút hoặc nút con.


```python
def remove_node(self, node_obj):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/vi/aspose.slides.smartart/ismartartnode) | Nút cần xóa. |



### Xem thêm
* lớp [`ISmartArtNode`](/slides/python-net/vi/aspose.slides.smartart/ismartartnode)
* lớp [`ISmartArtNodeCollection`](/slides/python-net/vi/aspose.slides.smartart/ismartartnodecollection)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)