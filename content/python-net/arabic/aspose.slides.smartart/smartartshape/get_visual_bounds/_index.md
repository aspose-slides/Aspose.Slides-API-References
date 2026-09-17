---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### القيم المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المعاد يمثل الحدود المحاذية للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم إلى ما وراء أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحولات (مثلاً، الدوران)، وعرض الخطوط والاتصالات، وتخطيط النص وتجاوزه، وجيومتريّات SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على الشكل النهائي للعرض.

الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)