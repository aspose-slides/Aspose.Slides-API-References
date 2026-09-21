---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتویات رندر شده آن محاسبه شده است، دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده‌شده، محدوده‌های محوری تمام محتوا را
             که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.

این محدوده‌ها ممکن است با محدوده‌های مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند
             و در صورت گسترش محتوای رندر شده فراتر از مبدأ اسلاید، ممکن است شامل مختصات منفی باشند.

حدود بصری، جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال چرخش)، عرض و اتصال خطوط قلم،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تاثیر می‌گذارند، در نظر می‌گیرند.

محدوده‌های بازگردانده‌شده به مستطیل اسلاید کلیپ نمی‌شوند.



### موارد مرتبط
* کلاس [`InkActions`](/slides/python-net/fa/aspose.slides.ink/inkactions)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)