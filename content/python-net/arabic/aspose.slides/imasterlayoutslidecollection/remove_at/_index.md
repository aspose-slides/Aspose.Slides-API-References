---
title: remove_at method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
يزيل العنصر في الفهرس المحدد من المجموعة.

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس الصفري للعنصر الذي سيُزال. |

### ملاحظات

1) لتجنب رفع استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط مسبقًا.
2) يمكنك أيضًا استخدام طريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الكود.

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمى إذا تم استخدام التخطيط في العرض التقديمي (خاصية HasDependingSlides لها قيمة true). |

### انظر أيضًا
* فئة [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)