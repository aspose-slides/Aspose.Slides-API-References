---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
يحصل على الحدود المرئية للشكل المحسوبة من محتواه المُرَسَم.

### الإرجاع
‏[`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) تمثّل الحدود المرئية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المعاد يمثل الحدود المحاذاة للمحور لجميع المحتوى
             المنتج من قبل الشكل أثناء التصيَر في مساحة إحداثيات الشريحة.


قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المُرَسَم
             خارج أصل الشريحة.

تأخذ الحدود المرئية في الاعتبار جوانب متعلقة بالتصيّر مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الحد والتقاطع،
             تخطيط النص وتجاوز المحتوى، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المُرَسَم للشكل.

الحدود المعادة ليست مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)