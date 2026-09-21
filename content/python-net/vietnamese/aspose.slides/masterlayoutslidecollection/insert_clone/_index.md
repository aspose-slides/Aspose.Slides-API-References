---
title: insert_clone method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Chèn một bản sao của slide bố cục được chỉ định vào vị trí đã chỉ định của bộ sưu tập.

### Trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục của slide mới. |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Ghi chú

Bố cục mới sẽ được liên kết với slide master cha cho bộ sưu tập slide bố cục này. Vì vậy đây là tương tự của sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`MasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)