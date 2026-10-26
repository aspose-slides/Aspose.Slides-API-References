---
title: insert_clone method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập.

### Giá trị trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |

### Ghi chú

Khi sao chép một slide giữa các bản trình bày khác nhau, master của slide cũng có thể được sao chép.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
Nếu bạn cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** hoặc
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** để sao chép slide và
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** để sao chép master.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập.

### Giá trị trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide) | Slide bố cục cho slide mới. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Chèn một bản sao của slide nguồn được chỉ định vào vị trí được chỉ định trong bộ sưu tập.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Giá trị trả về

Slide đã chèn.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số của slide mới. |
| source_slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Slide cần sao chép. |
| dest_master | [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide) | Master slide cho slide mới. |
| allow_clone_missing_layout | **bool** | Nếu không có bố cục phù hợp trong master được chỉ định thì bố cục của <br/><br/>            slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc <br/><br/>            PptxEditException sẽ được ném (nếu allowCloneMissingLayout là false). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu không có bố cục phù hợp trong master được chỉ định và allowCloneMissingLayout là false. |



### Xem thêm
* lớp [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide)
* lớp [`IMasterSlide`](/slides/python-net/vi/aspose.slides/imasterslide)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* lớp [`SlideCollection`](/slides/python-net/vi/aspose.slides/slidecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)