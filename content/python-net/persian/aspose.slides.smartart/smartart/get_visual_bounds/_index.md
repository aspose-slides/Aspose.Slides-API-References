---
title: get_visual_bounds method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
حدهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، دریافت می‌کند.

### بازگشت

یک [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) که حدهای بصری شکل را در مختصات اسلاید نشان می‌دهد
             در مختصات اسلاید.



```python
def get_visual_bounds(self):
    ...
```


### توضیحات

مستطیل بازگشتی نشان‌دهندهٔ حدهای محور تمام محتوایی است که توسط شکل در حین رندر در فضای مختصات اسلاید تولید می‌شود.
             
این حدها ممکن است با حدهای مدل شکل ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height)) متفاوت باشند و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد.
             
حدهای بصری عوامل مربوط به رندر مانند تبدیل‌ها (به عنوان مثال چرخش)، ضخامت و اتصال خطوط، چیدمان و سرریز متن، هندسه SmartArt و سایر اثرات چیدمانی که ظاهر نهایی رندر شدهٔ شکل را تحت تاثیر قرار می‌دهند را در نظر می‌گیرند.
             
حدهای بازگشتی به مستطیل اسلاید کلیپ نمی‌شوند.



### موارد مرتبط
* کلاس [`SmartArt`](/slides/python-net/fa/aspose.slides.smartart/smartart)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)