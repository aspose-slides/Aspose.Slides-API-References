---
title: formula property
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.animation/point/formula/
weight: 20
---
## خاصية الصيغة
يمكن أن تتكون الصيغ داخل القيم، وخصائص from، to، by من العناصر التالية:
            المشغلات الحسابية القياسية: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            الثوابت: ‘pi’ ‘e’
            المشغلات الشرطية: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            مشغلات المقارنة: '==', '>=', '', '!=', '!'
            المشغلات المثلثية: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            اللوغاريتم الطبيعي ‘ln()’
            مراجع الخصائص (خصائص المدعومة من المضيف)
            
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
* فئة [`Point`](/slides/python-net/ar/aspose.slides.animation/point)
* وحدة [`aspose.slides.animation`](/slides/python-net/ar/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)