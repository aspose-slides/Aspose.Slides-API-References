---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
مرزبندی بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### Returns

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که مرزبندی بصری شکل را در مختصات اسلاید نشان می‌دهد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

مستطیل برگردانده شده نمایانگر مرزبندی‌های محوری تمام محتویاتی است که توسط شکل در زمان رندر در فضای مختصات اسلاید تولید می‌شوند.
             
             این مرزبندی‌ها ممکن است با مرزبندی‌های مدل شکل
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             متفاوت باشند و اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشد.
             
             مرزبندی بصری عوامل مربوط به رندر مانند
             تبدیلات (به عنوان مثال، چرخش)، عرض و اتصال خطوط،
             چینش متن و سرریز، هندسه SmartArt و دیگر اثرات چیدمان
             که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.
             
             مرزبندی‌های برگردانده شده به مستطیل اسلاید کلیپ نمی‌شوند.



### See Also
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)