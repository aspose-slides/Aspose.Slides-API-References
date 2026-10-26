---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگشت‌شده، حدود محور به محور تمام محتوایی را که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورت گسترش محتوای رندر شده فراتر از مبدا اسلاید، ممکن است شامل مختصات منفی باشند.

حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصال خطوط قلم، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان را که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند، در نظر می‌گیرند.

حدود بازگشت‌شده به مستطیل اسلاید قطع (کلیپ) نمی‌شوند.



### موارد مرتبط
* کلاس [`GroupShape`](/slides/python-net/fa/aspose.slides/groupshape)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)