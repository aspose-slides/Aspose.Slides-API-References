---
title: get_visual_bounds method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يسترجع الحدود البصرية للشكل المحسوبة من محتواه المُرَسَم.

### الإرجاع

A **aspose.slides.RectangleF** التي تمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المُرجع يمثل الحدود المحاذية للمحور لجميع المحتويات
             الذي تنتجه الشكل أثناء التقديم في مساحة إحداثيات الشريحة.

             
قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المُرَسَم
             إلى ما وراء أصل الشريحة.

             
تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالتقديم مثل
             التحولات (على سبيل المثال، الدوران)، عرض الحد وحوافه،
             تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المُرَسَم للشكل.

             
الحدود المُرجعة لا يتم قصها إلى مستطيل الشريحة.



### انظر أيضاً
* الفئة [`GroupShape`](/slides/python-net/ar/aspose.slides/groupshape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)