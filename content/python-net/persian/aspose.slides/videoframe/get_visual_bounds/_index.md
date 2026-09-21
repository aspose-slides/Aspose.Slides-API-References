---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، به دست می‌آورد.

### Returns

یک **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

مستطیل بازگشتی نمایانگر مرزهای محور-محور تمام محتوایی است
             که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود.

این مرزها ممکن است با مرزهای مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
 و ممکن است در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، شامل مختصات منفی باشند.

حدود بصری عوامل مرتبط با رندر مانند
             تبدیل‌ها (به عنوان مثال، چرخش)، عرض و اتصال خطوط،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند.

مرزهای بازگشتی به مستطیل اسلاید قیچی نمی‌شوند.

### See Also
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)