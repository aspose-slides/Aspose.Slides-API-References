---
title: remove_at method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Xóa phần tử tại chỉ số được chỉ định trong bộ sưu tập.


```python
def remove_at(self, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 của phần tử cần xóa. |

### Ghi chú

Để tránh phát sinh PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của master trước.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu master cần xóa đang được sử dụng trong bản trình chiếu (thuộc tính HasDependingSlides của nó là true). |



### Xem thêm
* lớp [`MasterSlideCollection`](/slides/python-net/vi/aspose.slides/masterslidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)