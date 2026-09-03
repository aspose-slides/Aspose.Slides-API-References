---
title: get_image method
second_title: مرجع API لـ Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
يعيد صورة للفقرة.

### القيمة المرجعة

صورة تحتوي على الفقرة التي تم تصييرها، أو **None** إذا لم يتم العثور على الفقرة في مجموعة والدها، أو لا توجد حدود تصيير صالحة، أو حدث خطأ أثناء تصيير الصورة.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
يعيد صورة للفقرة بالمقياس المحدد.

### القيمة المرجعة

صورة تحتوي على الفقرة التي تم تصييرها، أو **None** إذا لم يتم العثور على الفقرة في مجموعة والدها، أو لا توجد حدود تصيير صالحة، أو حدث خطأ أثناء تصيير الصورة.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| scale_x | **float** | عامل القياس الأفقي المطبق على صورة الفقرة. |
| scale_y | **float** | عامل القياس العمودي المطبق على صورة الفقرة. |



### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* فئة [`Paragraph`](/slides/python-net/ar/aspose.slides/paragraph)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)