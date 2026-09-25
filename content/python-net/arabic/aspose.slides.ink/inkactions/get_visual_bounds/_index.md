---
title: get_visual_bounds method
second_title: Aspose.Slides للـ Python عبر مرجع API الخاص بـ .NET
description: 
type: docs
url: /ar/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل محسوبة من المحتوى المُرسَم.

### القيمة المرجعة

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المُرسَم
             خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحولات (على سبيل المثال، الدوران)، عرض الخط والاتصالات،
             تنسيق النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي للعرض للشكل.

الحدود المعادة لا تُقصَ إلى مستطيل الشريحة.

### انظر أيضًا
* فئة [`InkActions`](/slides/python-net/ar/aspose.slides.ink/inkactions)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* مكتبة [`Aspose.Slides`](/slides/python-net)