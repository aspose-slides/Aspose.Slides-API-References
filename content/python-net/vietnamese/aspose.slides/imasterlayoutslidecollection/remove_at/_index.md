---
title: remove_at method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập.


```python
def remove_at(self, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### Ghi chú

1) Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của layout trước.
2) Bạn cũng có thể sử dụng phương thức [`ILayoutSlide.remove`](/slides/python-net/vi/aspose.slides/ilayoutslide/remove) để đơn giản hoá mã.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu layout được sử dụng trong bản trình chiếu (thuộc tính HasDependingSlides của nó là đúng). |



### Xem thêm
* lớp [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)