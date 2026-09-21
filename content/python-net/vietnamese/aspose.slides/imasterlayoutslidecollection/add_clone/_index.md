---
title: add_clone method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Thêm một bản sao của slide bố cục được chỉ định vào cuối bộ sưu tập.

### Giá trị trả về

Slide được thêm.

```python
def add_clone(self, source_layout):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Ghi chú

1) Bố cục mới sẽ được liên kết với slide master cha cho bộ sưu tập các slide bố cục này.
   Vì vậy đây là tương tự của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.
2) Tương tự của phương pháp này là phương thức **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** được truy cập bằng thuộc tính [`IPresentation.layout_slides`](/slides/python-net/vi/aspose.slides/ipresentation/layout_slides).

### Xem Thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)