---
title: remove method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Xóa một bố cục khỏi bộ sưu tập.


```python
def remove(self, value):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Bố cục slide cần xóa khỏi bộ sưu tập. |

### Ghi chú

1) Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của layout trước.
2) Bạn cũng có thể sử dụng phương thức [`ILayoutSlide.remove`](/slides/python-net/vi/aspose.slides/ilayoutslide/remove) để đơn giản hoá code.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném ra nếu layout được sử dụng trong bản trình chiếu (thuộc tính HasDependingSlides của nó là true). |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`ILayoutSlideCollection`](/slides/python-net/vi/aspose.slides/ilayoutslidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)