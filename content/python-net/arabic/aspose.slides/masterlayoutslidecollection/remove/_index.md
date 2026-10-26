---
title: remove method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
يزيل تخطيطًا من المجموعة.

```python
def remove(self, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التخطيطية التي يجب إزالتها من المجموعة. |

### ملاحظات

1) لتجنب حدوث استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط مسبقًا.
2) يمكنك أيضًا استخدام الطريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الشيفرة.

### استثناءات

| استثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | تم إلقاؤه إذا تم استخدام التخطيط في العرض (خاصية HasDependingSlides له صحيحة). |

### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* الفئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)