---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
    in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

مستطیل بازگردانده شده نمایانگر مرزهای محور-محور تمام محتوایی است که توسط شکل در حین رندر در فضای مختصات اسلاید تولید می‌شود.
    
    این مرزها ممکن است با مرزهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و ممکن است مختصات منفی داشته باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
    
    حدود بصری جنبه‌های مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خط، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمانی که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.
    
    مرزهای بازگردانده شده به مستطیل اسلاید کلیپ نمی‌شوند.



### See Also
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)