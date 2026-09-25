---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌ آن محاسبه می‌شود، به‌دست می‌آورد.

### Returns
یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.


```python
def get_visual_bounds(self):
    ...
```


### Remarks
مستطیل بازگردانده‌شده نمایانگر حدود محوری تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشد و در صورت گسترش محتوای رندرشده فراتر از نقطهٔ آغاز اسلاید، ممکن است شامل مختصات منفی باشد.

حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض خط و اتصال‌ها، چیدمان و سرریز متن، هندسهٔ SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندرشدهٔ شکل تأثیر می‌گذارند، در نظر می‌گیرد.

حدود بازگردانده‌شده به مستطیل اسلاید قطع نمی‌شوند.



### See Also
* کلاس [`SummaryZoomFrame`](/slides/python-net/fa/aspose.slides/summaryzoomframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)