---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل التي تم حسابها من المحتوى المرسوم.

### القيمة المرجعة
[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) التي تمثل الحدود البصرية للشكل في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المعاد يمثل الحدود المتراصة على المحاور لجميع المحتويات التي ينتجها الشكل أثناء التقديم في مساحة إحداثيات الشريحة.
قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم خارج أصل الشريحة.
تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالتقديم مثل التحولات (على سبيل المثال، الدوران)، عرض الخط والفواصل، تخطيط النص وتجاوزاته، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.
الحدود المعادة غير مقصَّة إلى مستطيل الشريحة.

### انظر أيضًا
* الفئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* الفئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)