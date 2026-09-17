---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر .NET API المرجعية
description: 
type: docs
url: /ar/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المعروض.

### Returns

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

المستطيل المعاد يمثل الحدود المحاذية للمحور لكل المحتوى
             الذي ينتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض خارج أصل الشريحة.
            
             تأخذ الحدود البصرية في الاعتبار الجوانب المرتبطة بالعرض مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الحد وتوصيلاته،
             تخطيط النص والتجاوز، هندسة SmartArt، وغيرها من تأثيرات التنسيق
             التي تؤثر على المظهر النهائي المعروض للشكل.
            
             الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.



### See Also
* فئة [`AudioFrame`](/slides/python-net/ar/aspose.slides/audioframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)