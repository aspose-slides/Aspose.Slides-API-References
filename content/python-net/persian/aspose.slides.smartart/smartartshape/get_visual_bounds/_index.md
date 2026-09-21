---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### مقدار بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نمایش می‌دهد
             .

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل بازگردانده‌شده، مرزهای محور-محور تمام محتوایی را که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید شده است، نشان می‌دهد.
             
این مرزها ممکن است با مرزهای مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
             
حدود بصری، جنبه‌های مرتبط با رندر مانند
             تبدیل‌ها (مثلاً چرخش)، عرض و نوع خط،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرد.
             
مرزهای بازگردانده‌شده به مستطیل اسلاید قطع نمی‌شوند.

### مراجع
* کلاس [`SmartArtShape`](/slides/python-net/fa/aspose.slides.smartart/smartartshape)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)