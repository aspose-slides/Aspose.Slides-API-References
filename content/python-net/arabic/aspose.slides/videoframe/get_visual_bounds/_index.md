---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يحصل على الحدود البصرية للشكل المحسوبة من محتواه المرسوم.

### الإرجاع

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرتجع يمثل الحدود المحاذية للمحور لجميع المحتويات
             المنتجة بواسطة الشكل أثناء العرض في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المرسوم
             إلى ما بعد أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحويلات (على سبيل المثال، الدوران)، عرض الخطوط والالتقاء بينها،
             تخطيط النص والتجاوز، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المرسوم للشكل.

الحدود المرتجعة لا تُقَصَّ إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)