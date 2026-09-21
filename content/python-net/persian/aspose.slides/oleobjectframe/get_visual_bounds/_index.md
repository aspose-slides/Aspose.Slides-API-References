---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، برمی‌گرداند.

### Returns
بازگشت

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks
توضیحات

مستطیل بازگردانده شده، محدوده‌های محور-محور تمام محتوایی را که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود، نشان می‌دهد.

این محدوده‌ها ممکن است با محدوده‌های مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و در صورتی که محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد، ممکن است شامل مختصات منفی نیز باشند.

حدود بصری، جنبه‌های مرتبط با رندر مانند تبدیل‌ها (به عنوان مثال چرخش)، عرض خطوط و اتصال‌ها، چیدمان متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شدهٔ شکل تأثیر می‌گذارند را در نظر می‌گیرند.

محدوده‌های بازگردانده شده به مستطیل اسلاید قطع نمی‌شوند.



### See Also
موارد مرتبط
* کلاس [`OleObjectFrame`](/slides/python-net/fa/aspose.slides/oleobjectframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)