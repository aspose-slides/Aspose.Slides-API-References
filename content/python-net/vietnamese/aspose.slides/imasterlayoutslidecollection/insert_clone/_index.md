---
title: insert_clone method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Chèn một bản sao của slide bố cục được chỉ định vào vị trí xác định trong bộ sưu tập.

### Giá trị trả về

Slide đã chèn.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số của slide mới. |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Ghi chú

Bố cục mới sẽ được liên kết với slide master cha cho bộ sưu tập các slide bố cục này.
            Vì vậy đây là tương tự của copy/paste với "Use Destination Theme" option trong PowerPoint.

### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)