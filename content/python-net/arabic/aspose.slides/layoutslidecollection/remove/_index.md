---
title: remove method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
يزيل تخطيطًا من المجموعة.

```python
def remove(self, value):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة التخطيط لإزالتها من المجموعة. |

### ملاحظات

1) لتجنب حدوث PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط قبل ذلك.
2) يمكنك أيضًا استخدام طريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الكود.

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم إلقاؤه إذا تم استخدام التخطيط في العرض التقديمي (خاصية HasDependingSlides الخاصة به صحيحة). |

### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`LayoutSlideCollection`](/slides/python-net/ar/aspose.slides/layoutslidecollection)
* الفئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)