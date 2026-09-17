---
title: remove method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
يقوم بإزالة تخطيط من المجموعة.

```python
def remove(self, value):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة التخطيط التي سيتم إزالتها من المجموعة. |

### ملاحظات

1) لتجنب رمي استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط مسبقًا.  
2) يمكنك أيضًا استخدام طريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الشيفرة.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم رميه إذا كان التخطيط مستخدمًا في العرض التقديمي (خاصية HasDependingSlides الخاصة به صحيحة). |

### انظر أيضا
* فئة [`GlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/globallayoutslidecollection)
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)