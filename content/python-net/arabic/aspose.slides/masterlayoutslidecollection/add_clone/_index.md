---
title: add_clone method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

### الإرجاع
الشريحة المضافة.

```python
def add_clone(self, source_layout):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التي سيتم استنساخها. |

### ملاحظات
1) سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذه المجموعة من شرائح التخطيط.
            لذا هذا هو نظير النسخ/اللصق مع خيار "استخدام سمة الوجهة" في PowerPoint.
            2) نظير هذه الطريقة هو الطريقة **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            التي يتم الوصول إليها عبر الخاصية [`IPresentation.layout_slides`](/slides/python-net/ar/aspose.slides/ipresentation/layout_slides).

### راجع أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)