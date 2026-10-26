---
title: add_clone method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

### الإرجاع

شريحة جديدة.



```python
def add_clone(self, source_slide):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |

### ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ ماستر الشريحة أيضًا.
Internal registry is used to track automatically cloned masters to prevent creation of 
multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** أو
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** لاستنساخ الشرائح،
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** أو
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** لاستنساخ التخطيطات و
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** لاستنساخ الماسترات.



## add_clone(self, source_slide, section) {#islide-isection}
يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد.

### الإرجاع

شريحة جديدة.



```python
def add_clone(self, source_slide, section):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | القسم للشفرة الجديدة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

### الإرجاع

شريحة جديدة.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة التخطيط للشفرة الجديدة. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة.
سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي له نفس الـ Type أو الـ Name لتخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط الشريحة المصدر <br/><br/>            (إذا كان allowCloneMissingLayout صحيحًا) أو <br/><br/>            سيتم إثارة PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

### الإرجاع

شريحة جديدة.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | الشريحة الماستر للشفرة الجديدة. |
| allow_clone_missing_layout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد، فسيتم استنساخ تخطيط الشريحة المصدر <br/><br/>            (إذا كان allowCloneMissingLayout صحيحًا) أو <br/><br/>            سيتم إثارة PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم إثارة إذا لم يكن هناك تخطيط مناسب في الماستر المحدد و <br/>            allowCloneMissingLayout هو false. |



### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* الفئة [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* الفئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* الفئة [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection)
* الفئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)