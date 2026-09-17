---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل المحسوبة من محتواه المُرسَل.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المعاد يمثل الحدود المحاذية للمحور لجميع المحتويات
             التي ينتجها الشكل أثناء التقديم في فضاء إحداثيات الشريحة.
             
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا كان المحتوى المُرسَل يمتد
             خارج نقطة أصل الشريحة.
             
             الحدود البصرية تأخذ في الاعتبار الجوانب المتعلقة بالتقديم مثل
             التحويلات (مثلاً، الدوران)، عرض الخطوط والوصلات،
             تخطيط النص وتجاوزه، هندسة SmartArt، وتأثيرات تخطيط أخرى
             التي تؤثر على المظهر النهائي المُقدم للشكل.
             
             الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضا
* فئة [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)