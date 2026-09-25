---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود دریافت می‌کند.

### بازگرداندن

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده شده نشان‌دهنده حدود محورها موازی تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود ممکن است با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و ممکن است در صورت گسترش محتوای رندر شده فراتر از مبدأ اسلاید، شامل مختصات منفی شوند.

حدود بصری عوامل مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خطوط، چینش متن و سرریز، هندسه‌ی SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در نظر می‌گیرد.

حدود بازگردانده شده به مستطیل اسلاید محدود نشده‌اند.



### موارد مرتبط
* کلاس [`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)