---
title: get_visual_bounds method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل محسوبة من محتواه المعروض.

### الإرجاع

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرتجع يمثل الحدود المتراصة على المحاور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المعروض خارج أصل الشريحة.
            
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (مثلاً الدوران)، عرض الحد والاتصالات،
             تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التنسيق التي تؤثر على المظهر النهائي المعروض للشكل.
            
             الحدود المرتجعة ليست مقصَّة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SmartArt`](/slides/python-net/ar/aspose.slides.smartart/smartart)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)