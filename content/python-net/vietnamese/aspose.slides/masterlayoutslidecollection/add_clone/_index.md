---
title: add_clone method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Thêm một bản sao của slide bố cục được chỉ định vào cuối bộ sưu tập.

### Giá trị trả về

Slide đã thêm.



```python
def add_clone(self, source_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Ghi chú

1) Bố cục mới sẽ được liên kết với slide master cha cho bộ sưu tập các slide bố cục này.
            Do đó, đây là tương đương của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.
            2) Tương đương của phương thức này là phương thức **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            được truy cập bằng thuộc tính [`IPresentation.layout_slides`](/slides/python-net/vi/aspose.slides/ipresentation/layout_slides).

### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)