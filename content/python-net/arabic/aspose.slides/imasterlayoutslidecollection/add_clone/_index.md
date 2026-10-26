---
title: add_clone method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

### القيمة المرجعة

الشريحة المضافة.



```python
def add_clone(self, source_layout):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide) | الشريحة التي سيتم استنساخها. |

### ملاحظات

1) سيتم ربط التخطيط الجديد بالشريحة الرئيسة الأصلية لهذه مجموعة شرائح التخطيط.  
   لذلك هذا مماثل لعملية النسخ/اللصق مع خيار "استخدام نمط الوجهة" في PowerPoint.  
2) مماثل لهذه الطريقة هو الطريقة **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** التي يتم الوصول إليها عبر خاصية [`IPresentation.layout_slides`](/slides/python-net/ar/aspose.slides/ipresentation/layout_slides).

### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)