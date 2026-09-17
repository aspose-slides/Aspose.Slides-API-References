---
title: get_visual_bounds method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود المرئية للشكل المحسوبة من محتواه المرسوم.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود المرئية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرتجع يمثل الحدود المتراصة مع المحاور لجميع المحتويات
             التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم إلى ما بعد أصل الشريحة.
            
             تأخذ الحدود المرئية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (مثلاً، الدوران)، عرض الخطوط والتقاطع،
             تخطيط النص وتجاوز الحاوية، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المرسوم للشكل.
            
             الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* الصنف [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)