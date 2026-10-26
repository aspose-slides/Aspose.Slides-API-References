---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### القيمة المرجعة
كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرتجع يمثل الحدود المحاذاة للمحور لجميع المحتويات
             التي ينتجها الشكل أثناء الرسم في مساحة إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود النموذج للشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم
             إلى ما وراء أصل الشريحة.
            
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالرسم مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الخط والاتصالات،
             تخطيط النص والفيض، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المرسوم للشكل.
            
             الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`GroupShape`](/slides/python-net/ar/aspose.slides/groupshape)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)