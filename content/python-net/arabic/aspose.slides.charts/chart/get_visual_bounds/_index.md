---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### القيم المرجعة

**aspose.slides.RectangleF** وهو يمثل الحدود البصرية للشكل في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات

المستطيل المُعيد يمثل الحدود المحاذية للمحاور لجميع المحتويات التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.  
قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سلبية إذا كان المحتوى المُرسم يمتد خارج أصل الشريحة.  
تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الحد والوصلات، تخطيط النص وتجاوزه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.  
الحدود المُعادة غير مقصوصة إلى مستطيل الشريحة.

### انظر أيضًا
* الصنف [`Chart`](/slides/python-net/ar/aspose.slides.charts/chart)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)