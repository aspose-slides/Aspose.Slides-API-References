---
title: remove method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Xóa một bố cục khỏi bộ sưu tập.


```python
def remove(self, value):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Bản trình chiếu bố cục để xóa khỏi bộ sưu tập. |

### Ghi chú

1) Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của bố cục trước.
2) Bạn cũng có thể sử dụng phương thức [`ILayoutSlide.remove`](/slides/python-net/vi/aspose.slides/ilayoutslide/remove) để đơn giản hoá mã.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Ném ra nếu bố cục được sử dụng trong trình chiếu (thuộc tính HasDependingSlides của nó là true). |



### Xem thêm
* lớp [`GlobalLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/globallayoutslidecollection)
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)