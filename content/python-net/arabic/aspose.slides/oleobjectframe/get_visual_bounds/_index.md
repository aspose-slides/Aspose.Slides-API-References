---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل التي تم حسابها من المحتوى المُعَرض.

### القيم المرتجعة
كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المرجع يمثل الحدود المحاذية للمحاور لجميع المحتوى
             الذي ينتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض إلى ما وراء أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الخطوط والاتصالات،
             تخطيط النص والزيادة، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المرجعة لا يتم قصها إلى مستطيل الشريحة.

### انظر أيضًا
* فئة [`OleObjectFrame`](/slides/python-net/ar/aspose.slides/oleobjectframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)