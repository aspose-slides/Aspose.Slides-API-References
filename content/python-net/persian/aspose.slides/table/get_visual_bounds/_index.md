---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند.

### Returns

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

مستطیل بازگردانده شده نمایانگر حدود محور-محور تمام محتوایی است که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید شده است.
            
 این حدود ممکن است با حدود مدل شکل
 ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
 [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
 متفاوت باشد و ممکن است مختصات منفی داشته باشد اگر محتوای رندر شده فراتر از مبدا اسلاید گسترش یابد.
            
 حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصالات، چیدمان متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمان را که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند، در نظر می‌گیرد.
            
 محدوده‌های بازگردانده شده به مستطیل اسلاید کلیپ نمی‌شوند.



### See Also
* کلاس [`Table`](/slides/python-net/fa/aspose.slides/table)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)