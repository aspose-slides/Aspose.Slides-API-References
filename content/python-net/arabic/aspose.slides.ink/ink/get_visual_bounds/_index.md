---
title: get_visual_bounds method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يجلب الحدود البصرية للشكل المحسوبة من محتواها المرسوم.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المرتجع يمثل الحدود المحاذية للمحور لكل المحتوى
             المُنتج بواسطة الشكل أثناء العرض في مساحة إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم
             إلى ما وراء أصل الشريحة.
            
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (على سبيل المثال، الدوران)، عرض الخطوط والروابط،
             تخطيط النص والزيادة، هندسة SmartArt، وتأثيرات التخطيط الأخرى
             التي تؤثر على المظهر النهائي المرسوم للشكل.
            
             لا يتم قطع الحدود المرتجعة إلى مستطيل الشريحة.



### انظر أيضاً
* فئة [`Ink`](/slides/python-net/ar/aspose.slides.ink/ink)
* وحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* مكتبة [`Aspose.Slides`](/slides/python-net)