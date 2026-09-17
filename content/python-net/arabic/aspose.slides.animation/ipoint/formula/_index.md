---
title: formula property
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.animation/ipoint/formula/
weight: 10
---
## خاصية الصيغة
Formulas within values, from, to, by attributes can be made up of these:
            العوامل الحسابية القياسية: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            الثوابت: ‘pi’ ‘e’
            العوامل الشرطية: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            عوامل المقارنة: '==', '>=', '', '!=', '!'
            العوامل المثلثية: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            لوغاريتم طبيعي ‘ln()’
            مراجع الخصائص (الخصائص المدعومة من المضيف)
            
            على سبيل المثال: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            قراءة/كتابة **str**.

### التعريف:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### انظر أيضًا
* فئة [`IPoint`](/slides/python-net/ar/aspose.slides.animation/ipoint)
* وحدة [`aspose.slides.animation`](/slides/python-net/ar/aspose.slides.animation)
* مكتبة [`Aspose.Slides`](/slides/python-net)