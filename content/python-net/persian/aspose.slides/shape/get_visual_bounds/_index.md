---
title: get_visual_bounds method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود تصویری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند.

### بازگرداندن

[`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود تصویری شکل را در مختصات اسلاید نشان می‌دهد



```python
def get_visual_bounds(self):
    ...
```


### توضیحات
مستطیل بازگشتی نمایانگر حدود محور هم‌محور تمام محتوا
             تولید شده توسط شکل در حین رندر در فضای مختصات اسلاید.

این حدود ممکن است با حدود مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است در صورت گسترش محتوای رندر شده فراتر از مبدأ اسلاید، شامل مختصات منفی باشند.

حدود تصویری عوامل مرتبط با رندرینگ نظیر
تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصال‌ها،
قالب‌بندی متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمان
که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند، در نظر می‌گیرند.

حدود بازگشتی به مستطیل اسلاید برش داده نمی‌شوند.



### همچنین ببینید
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)