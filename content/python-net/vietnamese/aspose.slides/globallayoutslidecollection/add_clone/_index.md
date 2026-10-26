---
title: add_clone method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

### Trả về

Slide đã thêm.



```python
def add_clone(self, source_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Ghi chú

Khi sao chép một bố cục giữa các bản trình chiếu khác nhau, master của bố cục cũng có thể được sao chép để giữ định dạng nguồn.
Registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo nhiều bản sao của cùng một slide master.
Việc sao chép thủ công các slide master sẽ không bị ngăn chặn cũng như không được đăng ký.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

### Trả về

Slide đã thêm.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |
| dest_master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Slide master cho bố cục mới. |

### Ghi chú

1) Bố cục mới sẽ được liên kết với master đã định nghĩa trong bản trình chiếu đích.
   Vì vậy đây là tương tự việc sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.
2) Tương tự của phương pháp này là phương thức **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** được truy cập qua thuộc tính [`IMasterSlide.layout_slides`](/slides/python-net/vi/aspose.slides/imasterslide/layout_slides).



### Xem Thêm
* lớp [`GlobalLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/globallayoutslidecollection)
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)