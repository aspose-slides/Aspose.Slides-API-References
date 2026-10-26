---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه شده است، دریافت می‌کند.

### بازگشت

[`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)‌ای که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده‌شده نمایانگر حدود محورها محور‌شدهٔ تمام محتوایی است که شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌کند.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.

حدود بصری، جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال چرخش)، عرض و اتصالات خط، چیدمان متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند، در نظر می‌گیرند.

حدود بازگردانده‌شده به مستطیل اسلاید محدود نمی‌شوند.



### موارد مرتبط
* کلاس [`ZoomFrame`](/slides/python-net/fa/aspose.slides/zoomframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)