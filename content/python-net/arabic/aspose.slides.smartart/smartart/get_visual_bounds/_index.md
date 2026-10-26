---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل التي تم حسابها من محتواه المعروض.

### القيمة المرجعة

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرتجع يمثل الحدود المحاذية للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.
            
            قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
            وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض إلى ما بعد أصل الشريحة.
            
            تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الحد والتقانات، تخطيط النص وتدفقه، هندسة SmartArt، وتأثيرات تخطيط أخرى تؤثر على المظهر النهائي المعروض للشكل.
            
            الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SmartArt`](/slides/python-net/ar/aspose.slides.smartart/smartart)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)