---
title: get_visual_bounds method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل المحسوبة من محتواه المُعرض.

### القيمة المرجعة

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرتجع يمثل الحدود التي يتم محاذاتها مع المحاور لجميع المحتويات التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض إلى ما وراء أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار جوانب مرتبطة بالعرض مثل التحولات (على سبيل المثال، الدوران)، عرض الحد والواصلات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المرتجعة ليست مقصوصة إلى المستطيل الخاص بالشريحة.



### انظر أيضًا
* فئة [`Connector`](/slides/python-net/ar/aspose.slides/connector)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)