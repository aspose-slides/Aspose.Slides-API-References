---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود تصویری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، به‌دست می‌آورد.

### بازگشت

یک **aspose.slides.RectangleF** که حدود تصویری شکل را در مختصات اسلاید نشان می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### توضیحات

مستطیل بازگشتی، حدود محوری همهٔ محتواهایی که توسط شکل در حین رندر در فضای مختصات اسلاید تولید می‌شوند، نشان می‌دهد.  
این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.  
حدود تصویری، جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال چرخش)، عرض و اتصال خطوط، چیدمان متن و سرریز، هندسهٔ SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شدهٔ شکل تاثیر می‌گذارند، در نظر می‌گیرد.  
حدود بازگشتی به مستطیل اسلاید برش داده نمی‌شوند.

### مراجع
* کلاس [`ZoomFrame`](/slides/python-net/fa/aspose.slides/zoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)