---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يُحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### الإرجاع

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرجع يمثل الحدود المتحاذية للمحور لجميع المحتويات التي ينتجها الشكل أثناء التجسيد في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالتجسيد مثل التحولات (مثلاً، الدوران)، عرض الخطوط والاتصالات، تخطيط النص وتجاوزه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.

الحدود المرجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`Table`](/slides/python-net/ar/aspose.slides/table)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)