---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المعروض.

### الإرجاع

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل بإحداثيات الشريحة.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات

المستطيل المُرجَع يمثل الحدود المحاذية للمحور لجميع المحتويات
             التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

            قد تختلف هذه الحدود عن حدود نموذج الشكل
            ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
            وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض خارج أصل الشريحة.

            تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
            التحولات (مثلاً، الدوران)، عرض الخط وتقاطعاته،
            تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط
            التي تؤثر على المظهر النهائي المعروض للشكل.

            الحدود المُرجعة غير مقصّاة وفقًا لمستطيل الشريحة.

### انظر أيضًا
* الفئة [`ZoomFrame`](/slides/python-net/ar/aspose.slides/zoomframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)