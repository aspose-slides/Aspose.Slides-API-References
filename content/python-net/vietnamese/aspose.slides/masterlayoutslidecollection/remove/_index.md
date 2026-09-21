---
title: remove method
second_title: Aspose.Slides cho Python qua API .NET
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Xóa một bố cục khỏi bộ sưu tập.


```python
def remove(self, value):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Bản trình chiếu bố cục cần xóa khỏi bộ sưu tập. |

### Ghi chú

1) Để tránh việc ném PptxEditException, kiểm tra thuộc tính HasDependingSlides của bố cục trước.
2) Bạn cũng có thể sử dụng phương thức [`ILayoutSlide.remove`](/slides/python-net/vi/aspose.slides/ilayoutslide/remove) để đơn giản hoá mã.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu bố cục được sử dụng trong bản thuyết trình (thuộc tính HasDependingSlides của nó là true). |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)