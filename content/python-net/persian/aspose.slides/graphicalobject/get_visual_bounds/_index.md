---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns
یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
مستطیل بازگردانده‌شده نمایانگر مرزهای محوری تمام محتوا است
             تولید شده توسط شکل در حین رندر در فضای مختصات اسلاید.
            
             این مرزها ممکن است با مرزهای مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است شامل مختصات منفی باشد اگر محتوای رندر شده فراتر رود
             از مبدأ اسلاید.
            
             حدود بصری عوامل مرتبط با رندر را در نظر می‌گیرند مانند
             تبدیلات (مثلاً چرخش)، عرض خط و اتصالات،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند.
            
             مرزهای بازگردانده‌شده به مستطیل اسلاید محدود نمی‌شوند.



### See Also
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)