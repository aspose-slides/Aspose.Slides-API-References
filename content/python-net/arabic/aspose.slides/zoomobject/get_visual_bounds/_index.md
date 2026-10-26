---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يُحصل على الحدود البصرية للشكل المحسوبة من المحتوى المُعرض.

### القيمة المرجعة
[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) التي تمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المُرجَع يَمثِّل الحدود المحاذاة للمحور لكل المحتوى
             الذي ينتجه الشكل أثناء العرض في فضاء إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (على سبيل المثال، الدوران)، عرض الخطوط والموصلات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المُرجَعة ليست مقصّاة إلى مستطيل الشريحة.

### انظر أيضًا
* فئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)