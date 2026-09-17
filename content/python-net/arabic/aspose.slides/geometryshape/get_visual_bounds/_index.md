---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يُرجع الحدود البصرية للشكل محسوبةً من محتواه المعروض.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المُرجَع يمثل الحدود المحاذاة للمحور لجميع المحتويات التي يُنتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الخط والتوصيلات، تخطيط النص والتجاوز، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على الشكل النهائي المعروض للشكل.

الحدود المُرجَعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)