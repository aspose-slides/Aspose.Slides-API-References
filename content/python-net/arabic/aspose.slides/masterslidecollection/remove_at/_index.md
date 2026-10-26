---
title: remove_at method
second_title: Aspose.Slides للغة بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
يزيل العنصر الموجود في الفهرس المحدد للمجموعة.

```python
def remove_at(self, index):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري للعنصر الذي سيُزال. |

### ملاحظات

لتجنب رفع استثناء PptxEditException، تحقق من خاصية HasDependingSlides للماستر أولاً.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمى إذا تم استخدام الماستر الذي سيُزال في العرض (خاصية HasDependingSlides لديه صحيحة). |

### انظر أيضا
* فئة [`MasterSlideCollection`](/slides/python-net/ar/aspose.slides/masterslidecollection)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)