---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}

يتم الحصول على الحدود البصرية للشكل التي تم حسابها من محتواه المُرَسَم.

### القيمة المرجعة

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات

المستطيل المعاد يَمثّل حدود المحتوى المتوازية للمحاور
             الذي تنتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.

             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض
             بما يتجاوز أصل الشريحة.

             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (على سبيل المثال، الدوران)، عرض الحد وتقاطعاته،
             تخطيط النص وتدفقه، هندسة SmartArt، وتأثيرات التخطيط الأخرى
             التي تؤثر على المظهر النهائي المعروض للشكل.

             الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.

### انظر أيضًا
* الفئة [`AudioFrame`](/slides/python-net/ar/aspose.slides/audioframe)
* الفئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)