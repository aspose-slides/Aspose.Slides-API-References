---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود دریافت می‌کند.

### بازگشت

یک **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگشتی محدوده‌های هم‌محور تمام محتوایی که توسط شکل در زمان رندر در فضای مختصات اسلاید تولید می‌شود را نشان می‌دهد.
            
             این محدوده‌ها ممکن است با محدوده‌های مدل شکل متفاوت باشند ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) و ممکن است مختصات منفی داشته باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
            
             حدود بصری جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض قلم و اتصال‌ها، چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.
            
             محدوده‌های بازگشتی به مستطیل اسلاید قطع نمی‌شوند.



### موارد مرتبط
* کلاس [`Chart`](/slides/python-net/fa/aspose.slides.charts/chart)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)