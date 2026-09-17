---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل المحسوبة من محتواه المعروض.

### الإرجاع

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المعاد يمثل الحدود المحورية لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

هذه الحدود قد تختلف عن حدود نموذج الشكل
([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض خارج أصل الشريحة.

الحدود البصرية تأخذ في الاعتبار الجوانب المتعلقة بالعرض مثل التحولات (مثلاً، الدوران)، عرض الخطوط والاتصالات، تخطيط النص وتجاوزه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المعادة لا تُقَصّ إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SummaryZoomSection`](/slides/python-net/ar/aspose.slides/summaryzoomsection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)