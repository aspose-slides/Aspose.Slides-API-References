---
title: formula property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.animation/ipoint/formula/
weight: 10
---
## ویژگی formula
فرمول‌ها داخل مقادیر و ویژگی‌های **from**، **to**، **by** می‌توانند از موارد زیر تشکیل شوند:
            عملگرهای حسابی استاندارد: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            ثابت‌ها: ‘pi’ ‘e’
            عملگرهای شرطی: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            عملگرهای مقایسه‌ای: '==', '>=', '', '!=', '!'
            عملگرهای مثلثاتی: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            لگاریتم طبیعی ‘ln()’
            مراجع ویژگی (ویژگی‌های پشتیبانی‌شده توسط میزبان)
            
            برای مثال: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            خواندنی/نوشتنی **str**.

### تعریف:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### موارد مرتبط
* کلاس [`IPoint`](/slides/python-net/fa/aspose.slides.animation/ipoint)
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* کتابخانه [`Aspose.Slides`](/slides/python-net)