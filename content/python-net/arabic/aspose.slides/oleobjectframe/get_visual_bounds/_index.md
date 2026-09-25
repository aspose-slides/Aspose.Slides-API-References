---
title: get_visual_bounds method
second_title: Aspose.Slides لPython عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### القيمة المرجعة

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرتجع يمثل الحدود المتراصة على المحاور لكافة المحتوى
             الذي ينتجه الشكل أثناء التجسيد في مساحة إحداثيات الشريحة.
             
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم
             خارج أصل الشريحة.
             
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالتجسيد مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الخطوط والاتصالات،
             تخطيط النص والفيض، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المجسَّد للشكل.
             
             الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`OleObjectFrame`](/slides/python-net/ar/aspose.slides/oleobjectframe)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)