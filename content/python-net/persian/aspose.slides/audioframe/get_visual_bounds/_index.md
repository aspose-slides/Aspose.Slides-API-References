---
title: get_visual_bounds method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را نمایان می‌سازد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگردانده‌شده نشانگر حدود محوری تمام محتوا
             تولید شده توسط شکل در حین رندر در فضای مختصات اسلاید.
            
             این حدود ممکن است با حدود مدل شکل
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             متفاوت باشند و ممکن است شامل مختصات منفی شوند
             اگر محتوای رندر شده فراتر از مبدا اسلاید گسترش یابد.
            
             حدود بصری عوامل مرتبط با رندر مانند تبدیل‌ها (به عنوان مثال، چرخش)، عرض و اتصال خطوط، چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند را در بر می‌گیرد.
            
             حدود بازگردانده‌شده به مستطیل اسلاید بریده نمی‌شوند.



### موارد مرتبط
* کلاس [`AudioFrame`](/slides/python-net/fa/aspose.slides/audioframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)