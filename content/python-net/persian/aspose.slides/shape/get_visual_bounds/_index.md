---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه شده است به‌دست می‌آورد.

### بازده

A **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده‌شده، حدود محور‌محور تمام محتوایی را که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.
            
این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.
            
حدود بصری، جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خطوط، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرند.
            
حدود بازگردانده‌شده به مستطیل اسلاید برش نمی‌خورند.



### موارد مرتبط
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)