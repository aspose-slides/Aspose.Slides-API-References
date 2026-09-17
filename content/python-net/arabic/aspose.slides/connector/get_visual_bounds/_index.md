---
title: get_visual_bounds method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل المحسوبة من محتواه المجسَّد.

### القيمة المرجعة

**aspose.slides.RectangleF** الذي يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرجع يمثل الحدود المتراصفة على المحور لجميع المحتويات التي ينتجها الشكل أثناء التجسيد في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المجسَّد خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالتجسيد مثل التحولات (على سبيل المثال، الدوران)، عرض الحد والوصلات، تخطيط النص وتجاوز السطر، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المجسَّد للشكل.

الحدود المرجعة لا يتم قصها إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`Connector`](/slides/python-net/ar/aspose.slides/connector)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)