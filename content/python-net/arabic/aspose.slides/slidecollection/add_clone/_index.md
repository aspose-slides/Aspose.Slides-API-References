---
title: add_clone method
second_title: Aspose.Slides لـ Python عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

### القيمة المرجعة
شريحة جديدة.



```python
def add_clone(self, source_slide):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |

### ملاحظات
عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا استنساخ الماستر الخاص بالشريحة.
Internal registry is used to track automatically cloned masters to prevent creation of 
multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد.

### القيمة المرجعة
شريحة جديدة.



```python
def add_clone(self, source_slide, section):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | القسم للشريحة الجديدة. |

### الاستثناءات
| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

### القيمة المرجعة
شريحة جديدة.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة التخطيط للشريحة الجديدة. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### القيمة المرجعة
شريحة جديدة.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة الماستر للشريحة الجديدة. |
| allow_clone_missing_layout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد، فسيتم استنساخ تخطيط الشريحة <br/><br/>            المصدر (إذا كان allowCloneMissingLayout صحيح) أو <br/><br/>            سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout خطأ). |

### الاستثناءات
| استثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم رميه إذا لم يكن هناك تخطيط مناسب في الماستر المحدد و <br/>            allowCloneMissingLayout خطأ. |



### انظر أيضًا
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* فئة [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* فئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* فئة [`SlideCollection`](/slides/python-net/ar/aspose.slides/slidecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)