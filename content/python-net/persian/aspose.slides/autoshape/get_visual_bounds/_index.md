---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، برمی‌گرداند.

### بازگشت

A **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگشتی حدود محورمحور تمام محتوایی که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.
            
             این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و ممکن است در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید برود، شامل مختصات منفی شوند.
            
             حدود بصری جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصال خطوط، چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چینش که ظاهر نهایی رندر شدهٔ شکل را تحت تاثیر قرار می‌دهند را در نظر می‌گیرند.
            
             حدود بازگشتی به مستطیل اسلاید بریده نمی‌شوند.



### موارد مرتبط
* کلاس [`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)