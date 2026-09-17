---
title: get_visual_bounds method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يقوم بالحصول على الحدود البصرية للشكل محسوبة من محتواها المرسوم.

### القيمة المرجعة

كائن **aspose.slides.RectangleF** يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المرجع يمثل الحدود المحاذية للمحور لجميع المحتويات التي ينتجها الشكل أثناء العرض في مساحة إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height)) وقد تحتوي على إحداثيات سالبة إذا كان المحتوى المرسوم يمتد خارج أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (مثلاً، الدوران)، عرض الحدود والالتقاطات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المرسوم للشكل.

الحدود المرجعة لا تُقَصّ على مستطيل الشريحة.



### انظر أيضًا
* الفئة [`LegacyDiagram`](/slides/python-net/ar/aspose.slides/legacydiagram)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)