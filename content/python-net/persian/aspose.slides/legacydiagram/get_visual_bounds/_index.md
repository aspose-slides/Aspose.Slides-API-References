---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
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

مستطیل برگردانده شده نشان دهنده حدود محوری تمام محتواهایی است که توسط شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌شود.

این حدود می‌توانند با حدود مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدا اسلاید گسترش یابد، ممکن است شامل مختصات منفی باشند.

حدود بصری موارد مرتبط با رندر مانند تبدیلات (به عنوان مثال، چرخش)، عرض و اتصالات خط، چینش متن و سرریز، هندسه SmartArt و سایر اثرات چیدمان که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند را در نظر می‌گیرد.

حدود برگردانده شده به مستطیل اسلاید برش نمی‌شوند.

### موارد مرتبط
* کلاس [`LegacyDiagram`](/slides/python-net/fa/aspose.slides/legacydiagram)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)