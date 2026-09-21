---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns

یک **aspose.slides.RectangleF** که حدود بصری شکل را
             در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

مستطیل بازگردانده شده نشان‌دهنده حدود محور-محور تمام محتوایی است
             که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.
            
             این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشد و در صورتی که محتوای رندر شده
             فراتر از مبدأ اسلاید باشد، ممکن است شامل مختصات منفی باشد.
            
             حدود بصری عوامل مرتبط با رندر مانند تبدیل‌ها (به عنوان مثال، چرخش)،
             عرض و اتصالات خطوط، چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چینش
             که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند، در نظر می‌گیرد.
            
             حدود بازگردانده شده به مستطیل اسلاید کلیپ نمی‌شوند.



### See Also
* کلاس [`SummaryZoomSection`](/slides/python-net/fa/aspose.slides/summaryzoomsection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)