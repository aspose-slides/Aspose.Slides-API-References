---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### الإرجاع
كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرتجع يمثل الحدود المحاذية للمحاور لجميع المحتوى
             الناتج عن الشكل أثناء العرض في مساحة إحداثيات الشريحة.

هذه الحدود قد تختلف عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم
             إلى ما وراء أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الحد وتوصيلاته،
             تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المرتجعة لا تُقَصّ إلى مستطيل الشريحة.



### انظر أيضًا
* الفئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* الفئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)