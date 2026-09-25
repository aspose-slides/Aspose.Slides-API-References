---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل که از محتوای رندر شدهٔ آن محاسبه می‌شود را دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل برگشتی حدود محور-محور تمام محتوایی که توسط شکل در طول رندرینگ در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید باشد، ممکن است شامل مختصات منفی نیز باشند.

حدود بصری عوامل مرتبط با رندرینگ مانند تبدیل‌ها (به عنوان مثال، چرخش)، عرض و اتصال خطوط، چینش متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند را در نظر می‌گیرند.

حدود برگشتی بر مستطیل اسلاید بریده نمی‌شوند.

### موارد مرتبط

* کلاس [`SmartArtShape`](/slides/python-net/fa/aspose.slides.smartart/smartartshape)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)