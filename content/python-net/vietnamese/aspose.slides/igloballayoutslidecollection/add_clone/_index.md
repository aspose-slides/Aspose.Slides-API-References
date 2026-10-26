---
title: add_clone method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

### Returns

Slide đã thêm.



```python
def add_clone(self, source_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |

### Remarks

Khi sao chép một bố cục giữa các bản trình chiếu khác nhau, master của bố cục cũng có thể được sao chép để giữ định dạng gốc. Registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo ra nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn cản và cũng không được đăng ký.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Thêm một bản sao của slide bố cục được chỉ định vào bản trình chiếu.

### Returns

Slide đã thêm.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide để sao chép. |
| dest_master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Slide master cho một bố cục mới. |

### Remarks

Bố cục mới sẽ được liên kết với master được định nghĩa trong bản trình chiếu đích. Vì vậy, đây là tương tự của việc sao chép/dán với tùy chọn "Use Destination Theme" trong PowerPoint.



### Xem Thêm
* lớp [`IGlobalLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/igloballayoutslidecollection)
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)