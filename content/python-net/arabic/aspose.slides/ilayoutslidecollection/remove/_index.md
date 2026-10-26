---
title: remove method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
يزيل تخطيطًا من المجموعة.

```python
def remove(self, value):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | شريحة التخطيط لإزالتها من المجموعة. |

### ملاحظات

1) لتجنب رمي استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط أولاً.
2) يمكنك أيضًا استخدام طريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الشيفرة.

### استثناءات

| استثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمي إذا كان التخطيط مستخدمًا في العرض (خاصية HasDependingSlides الخاصة به صحيحة). |

### انظر أيضًا
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`ILayoutSlideCollection`](/slides/python-net/ar/aspose.slides/ilayoutslidecollection)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)