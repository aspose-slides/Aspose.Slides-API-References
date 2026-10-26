---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل برگردانده‌شده نشان‌دهنده حدود محور-محور تمام محتوایی است
             که توسط شکل در طول رندرینگ در فضای مختصات اسلاید تولید شده است.
            
             این حدود ممکن است با حدود مدل شکل متفاوت باشند
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است مختصات منفی داشته باشند اگر محتوا رندر شده
             فراتر از مبدای اسلاید گسترش یابد.
            
             حدود بصری عوامل مرتبط با رندرینگ را در نظر می‌گیرند، از جمله
             تبدیل‌ها (به عنوان مثال، چرخش)، عرض و اتصال خطوط،
             چینش متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که ظاهر نهایی رندر شده شکل را تحت تأثیر قرار می‌دهند.
            
             حدود برگردانده‌شده به مستطیل اسلاید قطع نمی‌شوند.



### موارد مرتبط
* کلاس [`SummaryZoomSection`](/slides/python-net/fa/aspose.slides/summaryzoomsection)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)