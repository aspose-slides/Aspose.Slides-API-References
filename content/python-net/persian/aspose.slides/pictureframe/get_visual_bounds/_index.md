---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل بازگردانده شده، حدود هم‌محور تمام محتوایی که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی شوند.

حدود بصری عواملی مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض خطوط و اتصالات، چینش متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرند.

حدود بازگردانده شده به مستطیل اسلاید محدود نمی‌شوند.

### موارد مرتبط
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)