---
title: get_visual_bounds method
second_title: مرجع Aspose.Slides للـ Python عبر .NET API
description: 
type: docs
url: /ar/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم.

### القيمة المرجعة
A [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
The returned rectangle represents the axis-aligned bounds of all content
             التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

             
             قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم إلى ما بعد أصل الشريحة.

             
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الضربة والاتصالات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.

             
             الحدود المرجعة ليست مقلمة داخل مستطيل الشريحة.

### انظر أيضاً
* الفئة [`Chart`](/slides/python-net/ar/aspose.slides.charts/chart)
* الفئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)