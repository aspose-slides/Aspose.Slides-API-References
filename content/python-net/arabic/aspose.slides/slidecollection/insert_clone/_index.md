---
title: insert_clone method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
يُدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

### القيمة المرجعة

الشريحة المدرجة.

```python
def insert_clone(self, index, source_slide):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |

### ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ رئيس الشريحة أيضًا.  
يتم استخدام سجل داخلي لتتبع الرؤوس المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الرئيس.  
ستتم عملية استنساخ يدوي لرؤوس الشرائح دون أن يتم منعها أو تسجيلها.  
إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** أو  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** لاستنساخ الشرائح و  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** لاستنساخ الرؤوس.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
يُدرج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

### القيمة المرجعة

الشريحة المدرجة.

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة تخطيط لشريحة جديدة. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
يُدرج نسخة من شريحة المصدر المحددة إلى الموضع المحدد في المجموعة.  
سيتم اختيار تخطيط مناسب تلقائيًا من الرئيس المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم ك تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن  
تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout غير صحيح).

### القيمة المرجعة

الشريحة المدرجة.

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة الرئيس لشريحة جديدة. |
| allow_clone_missing_layout | **bool** | إذا لم يكن هناك تخطيط مناسب في الرئيس المحدد فسيتم استنساخ تخطيط <br/><br/>            شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو <br/><br/>            سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout غير صحيح). |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمى إذا لم يكن هناك تخطيط مناسب في الرئيس المحدد و <br/>            allowCloneMissingLayout غير صحيح. |

### أنظر أيضًا
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* فئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* فئة [`SlideCollection`](/slides/python-net/ar/aspose.slides/slidecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)