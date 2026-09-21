---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که مرزهای بصری شکل را در مختصات اسلاید نشان می‌دهد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### ملاحظات

مستطیل بازگردانده شده نشان‌دهنده مرزهای محوری تمام محتوایی است که توسط شکل هنگام رندر در فضای مختصات اسلاید تولید می‌شود.
            
این مرزها ممکن است با مرزهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده از مبدأ اسلاید عبور کند، ممکن است شامل مختصات منفی باشند.
            
مرزهای بصری جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خط، چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرند.
            
مرزهای بازگردانده شده به مستطیل اسلاید محدود نمی‌شوند.



### همچنین ببینید
* کلاس [`GroupShape`](/slides/python-net/fa/aspose.slides/groupshape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)