---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند.

### بازگرداندن

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات

مستطیل بازگردانده‌شده، حدود محور-محور تمام محتوای تولید شده توسط شکل در طول رندرینگ در فضای مختصات اسلاید را نشان می‌دهد.

این حدود ممکن است با حدود مدل شکل متفاوت باشند ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدا اسلاید گسترش یابد.

حدود بصری عوامل مرتبط با رندرینگ مانند تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصال‌ها، طرح‌بندی متن و سرریز، هندسهٔ SmartArt، و سایر اثرات طرح‌بندی که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند را در نظر می‌گیرند.

حدود بازگردانده‌شده به مستطیل اسلاید قطع نمی‌شوند.

### همچنین ببینید
* کلاس [`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)