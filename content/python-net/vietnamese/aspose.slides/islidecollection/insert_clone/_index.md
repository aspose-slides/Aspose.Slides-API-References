---
title: insert_clone method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Chèn một bản sao của slide đã chỉ định vào vị trí được chỉ định trong bộ sưu tập.

### Trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |

### Ghi chú

Khi sao chép một slide giữa các bài thuyết trình khác nhau, master của slide cũng có thể được sao chép.
            Bộ đăng ký nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo nhiều bản sao của cùng một master slide.
            Việc sao chép thủ công các master slide sẽ không bị ngăn cản và cũng không được đăng ký.
            Nếu bạn cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** hoặc
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** để sao chép slide và
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** để sao chép master.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Chèn một bản sao của slide đã chỉ định vào vị trí được chỉ định trong bộ sưu tập.

### Trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Layout slide cho slide mới. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Chèn một bản sao của slide nguồn đã chỉ định vào vị trí được chỉ định trong bộ sưu tập.
            Layout phù hợp sẽ được tự động chọn từ master đã chỉ định 
            (layout phù hợp là layout có cùng Type hoặc Name với 
            layout của slide nguồn). Nếu không có layout phù hợp thì
            layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout 
            là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout
            là false).

### Trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |
| dest_master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Master slide cho slide mới. |
| allow_clone_missing_layout | **bool** | Nếu không có layout phù hợp trong master đã chỉ định thì layout của <br/><br/>            slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc <br/><br/>            sẽ ném PptxEditException (nếu allowCloneMissingLayout là false). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Ném ra nếu không có layout phù hợp trong master đã chỉ định và <br/>            allowCloneMissingLayout là false. |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`ISlideCollection`](/slides/python-net/vi/aspose.slides/islidecollection)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)