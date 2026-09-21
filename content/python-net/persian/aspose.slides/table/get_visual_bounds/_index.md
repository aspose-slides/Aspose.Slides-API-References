---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود دریافت می‌کند.

### بازگشت

A **aspose.slides.RectangleF** که نمایانگر مرزهای بصری شکل است
             در مختصات اسلاید.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات
مستطیل بازگردانده شده نشان‌دهنده حدود محور محور تمام محتوایی است
             که توسط شکل در حین رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی نیز شوند.

مرزهای بصری عوامل مرتبط با رندر مانند
             تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خطوط،
             چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که ظاهر نهایی رندر شدهٔ شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرند.

حدود بازگردانده شده به مستطیل اسلاید محدود نمی‌شوند.

### موارد مرتبط
* کلاس [`Table`](/slides/python-net/fa/aspose.slides/table)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)