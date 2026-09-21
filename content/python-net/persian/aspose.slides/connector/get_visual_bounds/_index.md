---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، برمی‌گرداند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل بازگردانده‌شده نمایانگر حدود محور-محور تمام محتوایی است که توسط شکل در طول رندرینگ در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید باشد، ممکن است شامل مختصات منفی شوند.

حدود بصری عوامل مرتبط با رندرینگ نظیر تبدیل‌ها (به عنوان مثال، چرخش)، عرض خط و اتصالات، چینش متن و سرریز، هندسهٔ SmartArt و سایر اثرات چینش که بر ظاهر نهایی رندر شدهٔ شکل تاثیر می‌گذارند، در نظر می‌گیرد.

حدود بازگردانده شده به مستطیل اسلاید محدود نمی‌شوند.

### همچنین ببینید
* کلاس [`Connector`](/slides/python-net/fa/aspose.slides/connector)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)