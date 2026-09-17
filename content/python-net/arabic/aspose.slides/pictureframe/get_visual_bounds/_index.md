---
title: get_visual_bounds method
second_title: Aspose.Slides للـ Python عبر مرجع API .NET
description: 
type: docs
url: /ar/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل المحسوبة من محتواه المُعَد.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

المستطيل المعاد يمثل الحدود المحاذية للمحاور لكافة المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سلبية إذا تمد المحتوى المعروض خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحولات (على سبيل المثال، الدوران)، عرض الخط والاتصالات، تنسيق النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* الفئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)