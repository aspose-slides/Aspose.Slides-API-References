---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر مرجع API لـ .NET
description: 
type: docs
url: /ar/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل التي تم حسابها من محتواها المرسوم.

### القيمة المرجعة
[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) الذي يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المرتجع يمثل الحدود المحاذية للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.
هذه الحدود قد تختلف عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم إلى ما وراء أصل الشريحة.
تأخذ الحدود البصرية في الحسبان الجوانب المتعلقة بالعرض مثل التحولات (على سبيل المثال، الدوران)، وعرض الخط والاتصالات، وتخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.
الحدود المرتجعة غير مقصّرة إلى مستطيل الشريحة.

### انظر أيضًا
* فئة [`Ink`](/slides/python-net/ar/aspose.slides.ink/ink)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* مكتبة [`Aspose.Slides`](/slides/python-net)