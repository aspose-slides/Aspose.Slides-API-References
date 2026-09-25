---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه شده است، دریافت می‌کند.

### بازگشت
[`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات
مستطیل بازگشت‌شده، مرزهای محور-محور تمام محتوایی که توسط شکل در طی رندر در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.

این مرزها ممکن است با مرزهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورت گسترش محتوای رندر شده فراتر از مبدأ اسلاید، ممکن است شامل مختصات منفی باشند.

حدود بصری عوامل مربوط به رندرینگ مانند تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصال‌ها، طرح-بندی متن و سرریز، هندسه SmartArt، و سایر اثرات طرح-بندی که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرند.

مرزهای بازگشت‌شده به مستطیل اسلاید قطع نمی‌شوند.

### موارد مرتبط
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)