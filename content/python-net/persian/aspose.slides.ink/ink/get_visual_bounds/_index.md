---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات
مستطیل بازگشتی نمایانگر حدود محور-محور تمام محتوایی است
             که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است در صورت گسترش محتوای رندر شده، مختصات منفی داشته باشند
             فراتر از مبدأ اسلاید.

حدود بصری عوامل مرتبط با رندرینگ مانند
             تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصالات،
             چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.

حدود بازگشتی به مستطیل اسلاید محدود نشده‌اند.



### موارد مرتبط
* کلاس [`Ink`](/slides/python-net/fa/aspose.slides.ink/ink)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)