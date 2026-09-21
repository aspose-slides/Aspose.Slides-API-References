---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns
یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
مستطیل برگردانده شده، حدود محوراً-هم‌راستا تمام محتوایی که شکل در طول رندر تولید می‌کند را در فضای مختصات اسلاید نشان می‌دهد.

این حدود ممکن است با حدود مدل shape ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.

حدود بصری جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصال‌ها، چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرند.

حدود برگردانده شده به مستطیل اسلاید قطع (کلیپ) نمی‌شوند.

### See Also
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)