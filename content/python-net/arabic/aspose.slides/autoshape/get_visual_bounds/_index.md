---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل التي تم حسابها من محتواه المرسوم.

### الإرجاع
كائن **aspose.slides.RectangleF** الذي يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
المستطيل المرجع يمثل الحدود المتراصة على المحاور لجميع المحتوى الذي ينتجه الشكل أثناء العرض في فضاء إحداثيات الشريحة.

             قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم إلى ما بعد أصل الشريحة.

             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الخط والاتصالات، تنسيق النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

             الحدود المرجعة ليست مقصوصة إلى مستطيل الشريحة.

### أنظر أيضًا
* فئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)