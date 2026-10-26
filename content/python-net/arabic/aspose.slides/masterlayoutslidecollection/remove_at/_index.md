---
title: remove_at method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
يزيل العنصر في الفهرس المحدد في المجموعة.


```python
def remove_at(self, index):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري للعنصر الذي سيُزال. |

### ملاحظات

1) لتجنب رمي استثناء PptxEditException تحقق من خاصية HasDependingSlides في التخطيط أولاً.
2) يمكنك أيضًا استخدام طريقة [`ILayoutSlide.remove`](/slides/python-net/ar/aspose.slides/ilayoutslide/remove) لتبسيط الشفرة.

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمي إذا كان التخطيط مستخدمًا في العرض (خاصية HasDependingSlides له صواب). |

### انظر أيضًا
* فئة [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)