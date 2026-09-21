---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل که از محتوای رندر شده آن محاسبه می‌شود را دریافت می‌کند.

### بازگرداندن

یک **aspose.slides.RectangleF** که مرزهای بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانی شده مرزهای محور-محور تمام محتوایی را که
             توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.
            
             این مرزها ممکن است با مرزهای مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است مختصات منفی داشته باشند اگر محتوای رندر شده
             فراتر از مبدأ اسلاید گسترش یابد.
            
             مرزهای بصری جوانب مربوط به رندر مانند
             تبدیلات (به عنوان مثال چرخش)، عرض و اتصال خطوط،
             چینش متن و سرریز، هندسه SmartArt و سایر اثرات چینشی
             که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرد.
            
             مرزهای بازگردانی شده به مستطیل اسلاید قطع نمی‌شوند.



### موارد مرتبط
* کلاس [`SummaryZoomFrame`](/slides/python-net/fa/aspose.slides/summaryzoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)