---
title: insert_clone method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
يدرج نسخة من شريحة محددة في الموقع المحدد في المجموعة.

### القيمة المرجعة

الشريحة التي تم إدراجها.



```python
def insert_clone(self, index, source_slide):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |

### ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ ماستر الشريحة أيضًا.
            يُستخدم السجل الداخلي لتتبع العُمالات المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر.
            لن يتم حظر أو تسجيل الاستنساخ اليدوي لشرائح الماستر.
            إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** أو
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** لاستنساخ الشرائح و
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** لاستنساخ الماسترات.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
يدرج نسخة من شريحة محددة في الموقع المحدد في المجموعة.

### القيمة المرجعة

الشريحة التي تم إدراجها.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | تخطيط الشريحة للشرائح الجديدة. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
يدرج نسخة من شريحة المصدر المحددة في الموضع المحدد في المجموعة.
            سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد
            (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل
            تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب
            سيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout
            صحيحًا) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout
            خاطئًا).

### القيمة المرجعة

الشريحة التي تم إدراجها.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الشريحة التي سيتم استنساخها. |
| dest_master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة الماستر للشرائح الجديدة. |
| allow_clone_missing_layout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فإن تخطيط <br/><br/>            شريحة المصدر سيتم استنساخه (إذا كان allowCloneMissingLayout صحيحًا) أو <br/><br/>            سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم رميه إذا لم يكن هناك تخطيط مناسب في الماستر المحدد و <br/>            allowCloneMissingLayout خاطئ. |



### انظر أيضًا
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* فئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* فئة [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)