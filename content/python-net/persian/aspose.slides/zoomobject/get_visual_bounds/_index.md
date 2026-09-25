---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
مرزهای بصری شکل را که از محتوای رندر شده‌ آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که مرزهای بصری شکل را در
             مختصات اسلاید نمایش می‌دهد.

```python
def get_visual_bounds(self):
    ...
```

### ملاحظات
مستطیل بازگردانده شده، مرزهای هم‌محور تمام محتوا
             که توسط شکل در زمان رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.

             این مرزها ممکن است با مرزهای مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است شامل مختصات منفی شوند اگر محتوای رندر شده
             فراتر از مبدأ اسلاید گسترش یابد.

             مرزهای بصری، جنبه‌های مرتبط با رندر مانند
             تبدیلات (مثلاً چرخش)، عرض خط و اتصال‌ها،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند.

             مرزهای بازگردانده شده به مستطیل اسلاید برش داده نمی‌شوند.

### موارد مرتبط
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)