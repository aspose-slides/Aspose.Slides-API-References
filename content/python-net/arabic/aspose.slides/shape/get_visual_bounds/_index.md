---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل المحسوبة من المحتوى المُرَسَم.

### القيم المرجعة
A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المُرجَع يمثل الحدود المتوازية للمحاور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

هذه الحدود قد تختلف عن حدود نموذج الشكل
([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المُرَسَم
خارج أصل الشريحة.

الحدود البصرية تأخذ في الاعتبار الجوانب المتعلقة بالعرض مثل
التحويلات (على سبيل المثال، الدوران)، عرض الخطوط والاتصالات،
تخطيط النص والفيض، هندسة SmartArt، وغيرها من تأثيرات التخطيط
التي تؤثر على المظهر النهائي المُرَسَم للشكل.

الحدود المُرجَعة غير مقصوصة داخل مستطيل الشريحة.



### انظر أيضاً
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)