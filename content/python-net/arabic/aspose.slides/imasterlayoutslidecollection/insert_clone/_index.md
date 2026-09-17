---
title: insert_clone method
second_title: مرجع API لـ Aspose.Slides for Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
يُدرج نسخة من شريحة تخطيط محددة في الموضع المحدد في المجموعة.

### القيمة المرجعة

الشريحة التي تم إدراجها.



```python
def insert_clone(self, index, source_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة للاستنساخ. |

### ملاحظة

سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذا التجميع من شرائح التخطيط.
            لذا فهذا ما يعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.



### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)