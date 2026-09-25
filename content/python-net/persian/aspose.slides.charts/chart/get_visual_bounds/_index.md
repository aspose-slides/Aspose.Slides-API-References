---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگرداندن
یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات
مستطیل بازگردانده‌شده نشان‌دهنده حدود محور-محور تمام محتوایی است که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشد و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشد.

حدود بصری عوامل مرتبط با رندر مانند تبدیلات (برای مثال چرخش)، عرض و اتصال خطوط، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.

حدود بازگردانده‌شده به مستطیل اسلاید برش داده نمی‌شوند.

### همچنین ببینید
* کلاس [`Chart`](/slides/python-net/fa/aspose.slides.charts/chart)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)