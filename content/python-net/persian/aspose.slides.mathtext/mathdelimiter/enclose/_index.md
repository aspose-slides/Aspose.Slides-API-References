---
title: enclose method
second_title: مستندات API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
یک عنصر ریاضی را در پرانتز می‌پیچاند

### بازگشت

عنصر ریاضی از نوع [`IMathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter) که شامل پرانتز است



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
یک عنصر ریاضی را در کاراکترهای مشخصی مانند پرانتز یا کاراکترهای دیگر به عنوان قاب می‌گیرد

### بازگشت

اگر `beginning_character` و `ending_character` برابر None باشند، ویژگی‌های مربوطه فقط مقادیر اختصاص می‌یابند و هیچ شیء جدیدی ساخته نمی‌شود (این نمونه بازگردانده می‌شود).
در غیر این صورت، یک عنصر ریاضی جدید از نوع Delimiter باز می‌گرداند که کاراکترهای مشخص شده را به عنوان قاب شامل می‌شود و این نمونه از [`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter) درون آن قالب‌بندی می‌شود.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| beginning_character | **char** | کاراکتر شروع (معمولاً پرانتز چپ) |
| ending_character | **char** | کاراکتر پایان (معمولاً پرانتز راست) |



### موارد مرتبط
* کلاس [`IMathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/imathdelimiter)
* کلاس [`MathDelimiter`](/slides/python-net/fa/aspose.slides.mathtext/mathdelimiter)
* ماژول [`aspose.slides.mathtext`](/slides/python-net/fa/aspose.slides.mathtext)
* کتابخانه [`Aspose.Slides`](/slides/python-net)