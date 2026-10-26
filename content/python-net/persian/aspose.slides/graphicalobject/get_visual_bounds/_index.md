---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدود بصری شکل را که از محتوای رندر شده آن محاسبه شده است، دریافت می‌کند.

### بازگشت

[`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) ای که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات
مستطیل بازگردانده شده نمایانگر حدود محوری تمام محتوا است
             تولید شده توسط شکل در طول رندر در فضای مختصات اسلاید.

             
این حدود ممکن است با حدود مدل شکل متفاوت باشد
             ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
             و ممکن است در صورت گسترش محتوای رندر شده مختصات منفی داشته باشد
             فراتر از مبدأ اسلاید.

             
حدود بصری عوامل مرتبط با رندر را در نظر می‌گیرد مانند
             تبدیل‌ها (به عنوان مثال، چرخش)، عرض قلم و پیوست‌ها،
             چیدمان متن و سرریز، هندسه SmartArt، و سایر اثرات چیدمان
             که بر ظاهر نهایی رندر شده شکل تأثیر می‌گذارند.

             
حدود بازگردانده شده به مستطیل اسلاید محدود نمی‌شوند.



### مراجع
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)