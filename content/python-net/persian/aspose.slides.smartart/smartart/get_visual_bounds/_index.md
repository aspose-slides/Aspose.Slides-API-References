---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نمایش می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده شده نمایانگر حدود محوری تمام محتوایی است که شکل هنگام رندر در فضای مختصات اسلاید تولید می‌کند.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدا اسلاید برود، ممکن است شامل مختصات منفی باشند.

حدود بصری عوامل مرتبط با رندر مانند تبدیل‌ها (به عنوان مثال چرخش)، عرض و اتصالات خط، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.

حدود بازگردانده شده به مستطیل اسلاید قطع (کلیک) نشده‌اند.



### همچنین ببینید
* کلاس [`SmartArt`](/slides/python-net/fa/aspose.slides.smartart/smartart)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)