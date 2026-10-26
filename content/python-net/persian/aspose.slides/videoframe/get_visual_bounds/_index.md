---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل را که از محتوای رندر شده‌ آن محاسبه می‌شود، برمی‌گرداند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که مرزهای بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل برگردانده شده، مرزهای هم‌محور تمام محتوایی  
که توسط شکل در طول رندرینگ در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.  

این مرزها ممکن است با مرزهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),  
[`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورت گسترش محتوای رندر شده فراتر از مبدأ اسلاید، ممکن است شامل مختصات منفی شوند.  

مرزهای بصری، جوانب مرتبط با رندرینگ مانند تبدیلات (برای مثال، چرخش)، ضخامت و اتصالات خطوط، صفحه‌بندی متن و سرریز، هندسه SmartArt، و سایر اثرات لایه‌بندی که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند، را در نظر می‌گیرند.  

مرزهای برگردانده شده به مستطیل اسلاید قطع نمی‌شوند.

### موارد مرتبط
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)