---
title: get_visual_bounds method
second_title: Aspose.Slides للـ Python عبر .NET API Reference
description: 
type: docs
url: /ar/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل محسوبة من محتواه المعروض.

### إرجاع

[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) تمثل الحدود البصرية للشكل في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات

المستطيل المرجع يمثل الحدود المحاذاة للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحولات (على سبيل المثال، الدوران)، عرض الخطوط والالتقاءات، تخطيط النص والازدواج، هندسة SmartArt، وتأثيرات تخطيطية أخرى تؤثر على المظهر النهائي المعروض للشكل.

الحدود المرجعة غير مقصوصة إلى مستطيل الشريحة.

### انظر أيضًا
* الفئة [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe)
* الفئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)