---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند.

### Returns

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

مستطیل بازگشتی نمایانگر حدود محوری تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.
            
این حدود ممکن است با حدود مدل شکل متفاوت باشد
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است شامل مختصات منفی باشد اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
            
حدود بصری به جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات قلم، چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که ظاهر نهایی رندر شدهٔ شکل را تحت تأثیر قرار می‌دهند، توجه می‌کند.
            
حدود بازگشتی به مستطیل اسلاید کلیپ نشده‌اند.



### See Also
* کلاس [`Ink`](/slides/python-net/fa/aspose.slides.ink/ink)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)