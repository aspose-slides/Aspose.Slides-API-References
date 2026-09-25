---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، دریافت می‌کند.

### Returns
یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
مستطیل بازگشتی نمایانگر حدود محوری تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.  
این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.  
حدود بصری عوامل مربوط به رندر مانند تبدیل‌ها (مثلاً چرخش)، عرض خط و اتصالات، چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند، در نظر می‌گیرند.  
حدود بازگشتی به مستطیل اسلاید محدود نمی‌شوند.



### See Also
* کلاس [`SectionZoomFrame`](/slides/python-net/fa/aspose.slides/sectionzoomframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)