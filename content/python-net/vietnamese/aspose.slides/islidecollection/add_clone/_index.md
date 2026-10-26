---
title: add_clone method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập.

### Trả về

Slide mới.



```python
def add_clone(self, source_slide):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide để sao chép. |

### Ghi chú

Khi sao chép một slide giữa các bản thuyết trình khác nhau, master của slide cũng có thể được sao chép.
            Registry nội bộ được dùng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo
            nhiều bản sao của cùng một master slide.
            Việc sao chép thủ công các master slide sẽ không bị ngăn cản hoặc được ghi nhận.
            Nếu bạn cần kiểm soát nhiều hơn quá trình sao chép, sử dụng
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** hoặc
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** để sao chép slide,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** hoặc
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** để sao chép layout và
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** để sao chép master.


## add_clone(self, source_slide, section) {#islide-isection}
Thêm một bản sao của slide đã chỉ định vào cuối phần đã chỉ định.

### Trả về

Slide mới.



```python
def add_clone(self, source_slide, section):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide để sao chép. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | Phần cho slide mới. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập.

### Trả về

Slide mới.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide để sao chép. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Layout slide cho slide mới. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Thêm một bản sao của slide nguồn đã chỉ định vào cuối bộ sưu tập.
            Layout phù hợp sẽ được chọn tự động từ master đã chỉ định
            (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp thì
            layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc PptxEditException sẽ được ném ra (nếu allowCloneMissingLayout là false).

### Trả về

Slide mới.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide để sao chép. |
| dest_master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Master slide cho slide mới. |
| allow_clone_missing_layout | **bool** | Nếu không có layout phù hợp trong master đã chỉ định thì layout của <br/><br/>            slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc <br/><br/>            PptxEditException sẽ được ném ra (nếu allowCloneMissingLayout là false). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu không có layout phù hợp trong master đã chỉ định và <br/>            allowCloneMissingLayout là false. |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* lớp [`ISection`](/slides/python-net/vi/aspose.slides/isection)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`ISlideCollection`](/slides/python-net/vi/aspose.slides/islidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)