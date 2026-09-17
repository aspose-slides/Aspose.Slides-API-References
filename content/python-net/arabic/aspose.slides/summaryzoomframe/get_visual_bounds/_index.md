---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل المُحتسبة من المحتوى المُعرض.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المعاد يمثل الحدود المتراصة مع المحور لكل المحتوى الذي ينتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.
             
هذه الحدود قد تختلف عن حدود نموذج الشكل
([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض خارج أصل الشريحة.
             
الحدود البصرية تأخذ في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الخط والاتصالات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.
             
الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SummaryZoomFrame`](/slides/python-net/ar/aspose.slides/summaryzoomframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)