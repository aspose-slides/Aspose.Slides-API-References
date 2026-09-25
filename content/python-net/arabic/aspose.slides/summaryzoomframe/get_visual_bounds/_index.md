---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من المحتوى المعروض.

### الإرجاع

[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) الذي يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرجع يمثل الحدود المتراصة على المحاور لجميع المحتوى
             الذي ينتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.

هذه الحدود قد تختلف عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا كان المحتوى المعروض يمتد
             خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (على سبيل المثال، الدوران)، عرض الخطوط والاتصالات،
             تنسيق النص والتجاوز، هندسة SmartArt، وتأثيرات التخطيط الأخرى
             التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المرجعة ليست مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SummaryZoomFrame`](/slides/python-net/ar/aspose.slides/summaryzoomframe)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)