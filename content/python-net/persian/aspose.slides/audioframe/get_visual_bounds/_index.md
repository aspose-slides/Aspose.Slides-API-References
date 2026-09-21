---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل را که از محتوای رندرسازی شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns
یک **aspose.slides.RectangleF** که مرزهای بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
مستطیل بازگشتی نمایانگر مرزهای هم-محور تمام محتوایی است که توسط شکل در زمان رندرسازی در فضای مختصات اسلاید تولید می‌شود.

این مرزها ممکن است با مرزهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.

مرزهای بصری عوامل مرتبط با رندر را در نظر می‌گیرند، از جمله تبدیل‌ها (مانند چرخش)، عرض خط و اتصالات، چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندرسازی شده شکل تأثیر می‌گذارند.

مرزهای بازگشتی به مستطیل اسلاید قطع نشده‌اند.



### See Also
* کلاس [`AudioFrame`](/slides/python-net/fa/aspose.slides/audioframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)