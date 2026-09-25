---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، دریافت می‌کند.

### بازمی‌گرداند

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات
The returned rectangle represents the axis-aligned bounds of all content
             که شکل در طی رندر در فضای مختصات اسلاید تولید می‌کند.

             
             این حدود ممکن است با حدود مدل شکل
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             متفاوت باشد و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
             
             
             حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصال خطوط، چینش متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان را در نظر می‌گیرند که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند.
             
             
             حدود بازگشت یافته به مستطیل اسلاید برش داده نمی‌شوند.



### موارد مرتبط
* کلاس [`InkActions`](/slides/python-net/fa/aspose.slides.ink/inkactions)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)