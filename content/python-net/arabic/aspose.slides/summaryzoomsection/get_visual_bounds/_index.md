---
title: get_visual_bounds method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
يعيد الحدود البصرية للشكل التي تم حسابها من المحتوى المرسوم.

### الإرجاع

كائن [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) يمثل الحدود البصرية للشكل
             في إحداثيات الشريحة.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات
 المستطيل المرتجع يمثل الحدود المحاذية للمحور لكافة المحتوى الذي ينتجه الشكل أثناء العرض في مساحة إحداثيات الشريحة.
            
            قد تختلف هذه الحدود عن حدود نموذج الشكل ([`Shape.x`](/slides/python-net/ar/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ar/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/ar/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ar/aspose.slides/shape/height))
            وقد تحتوي على إحداثيات سالبة إذا كان المحتوى المرسوم يمتد خارج أصل الشريحة.
            
            تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحويلات (على سبيل المثال، الدوران)، عرض الحد وتقواها، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي للشكل.
            
            الحدود المرتجعة غير مقصوصة إلى مستطيل الشريحة.



### انظر أيضًا
* فئة [`SummaryZoomSection`](/slides/python-net/ar/aspose.slides/summaryzoomsection)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)