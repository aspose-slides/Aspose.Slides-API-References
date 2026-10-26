---
title: remove method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Xóa bố cục khỏi bản trình chiếu.

```python
def remove(self):
    ...
```

### Ghi chú
Để tránh ném PptxEditException, kiểm tra thuộc tính HasDependingSlides của layout trước.

### Ngoại lệ
| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu layout đã được xóa khỏi bản trình chiếu hoặc nếu layout được sử dụng trong bản trình chiếu (its <br/>            HasDependingSlides property is true). |

### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)