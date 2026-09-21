---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده‌شده نمایانگر حدود محوری تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی شوند.

حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصال خطوط، چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان را که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند، در نظر می‌گیرند.

حدود بازگردانده‌شده به مستطیل اسلاید محدود نشده‌اند.



### موارد دیگر
* class [`LegacyDiagram`](/slides/python-net/fa/aspose.slides/legacydiagram)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)