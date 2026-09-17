---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُرسَم.

### القيم المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المُرجَع يمثل الحدود المتراصة مع المحاور لكل المحتوى
             الذي يُنتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.
             
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم
             إلى ما وراء أصل الشريحة.
             
             تأخذ الحدود البصرية في الاعتبار جوانب مرتبطة بالعرض مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الحد وتوصيلاته،
             تخطيط النص وتدفقه، هندسة SmartArt، وتأثيرات تخطيط أخرى
             تؤثر على الشكل النهائي المعروض للشكل.
             
             الحدود المُرجَعة لا تُقَص إلى مستطيل الشريحة.



### انظر أيضًا
* الفئة [`Table`](/slides/python-net/ar/aspose.slides/table)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)