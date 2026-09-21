---
title: insert_clone method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
یک کپی از اسلاید مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.

### بازگرداندن

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلایدی که باید کلون شود. |

### توضیحات

هنگام کلون‌کردن اسلاید بین ارائه‌های مختلف، مستر اسلاید نیز می‌تواند کلون شود.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
یک کپی از اسلاید مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.

### بازگرداندن

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلایدی که باید کلون شود. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide) | اسلاید چینش برای اسلاید جدید. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
یک کپی از اسلاید منبع مشخص شده را در موقعیت تعیین‌شدهٔ مجموعه وارد می‌کند.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### بازگرداندن

اسلاید وارد شده.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص اسلاید جدید. |
| source_slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلایدی که باید کلون شود. |
| dest_master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | مستر اسلاید برای اسلاید جدید. |
| allow_clone_missing_layout | **bool** | اگر در مستر مشخص‌شده طرح‌بندی مناسب وجود نداشته باشد، طرح‌بندی اسلاید <br/><br/>            منبع کلون خواهد شد (اگر allowCloneMissingLayout برابر true باشد) یا <br/><br/>            PptxEditException پرتاب می‌شود (اگر allowCloneMissingLayout برابر false باشد). |

### استثناها

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | در صورتی که در مستر مشخص‌شده طرح‌بندی مناسب وجود نداشته باشد و <br/>            allowCloneMissingLayout برابر false باشد، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`ISlideCollection`](/slides/python-net/fa/aspose.slides/islidecollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)