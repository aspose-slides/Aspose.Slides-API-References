---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
يُحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم.

### القيم المرجعة
كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
المستطيل المُرجَع يمثل الحدود المحاذية للمحور لجميع المحتويات
             التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة.
            
             قد تختلف هذه الحدود عن حدود نموذج الشكل
             ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
             وقد تحتوي على إحداثيات سلبية إذا امتد المحتوى المرسوم
             خارج أصل الشريحة.
            
             تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل
             التحويلات (على سبيل المثال، دوران)، عرض الخطوط والوصالات،
             تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط
             التي تؤثر على المظهر النهائي المرسوم للشكل.
            
             لا يتم قطع الحدود المرجعة إلى مستطيل الشريحة.



### انظر أيضا
* فئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)