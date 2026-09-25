---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المصور.

### الإرجاع
[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المرتجع يمثل الحدود المحاذاة للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.
قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض إلى ما بعد أصل الشريحة.
تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، وعرض الحد والاتصالات، وتنسيق النص وتدفقه، وهندسة SmartArt، وتأثيرات التخطيط الأخرى التي تؤثر على المظهر النهائي المعروض للشكل.
الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.

### انظر أيضًا
* فئة [`ZoomFrame`](/slides/python-net/ar/aspose.slides/zoomframe)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)