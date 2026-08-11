---
title: IsSurrogatePair()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا دو کاراکتر مشخص شده برای یک جفت surrogate UTF-16 هستند.
type: docs
weight: 27
url: /fa/system/char/issurrogatepair/
---
## متد Char::IsSurrogatePair(char_t, char_t)


تعیین می‌کند که آیا دو کاراکتر مشخص شده برای یک جفت surrogate UTF-16 هستند یا خیر.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| highSurrogate | char_t | کاراکتری که برای بودن به‌عنوان high surrogate مورد آزمایش قرار می‌گیرد |
| lowSurrogate | char_t | کاراکتری که برای بودن به‌عنوان low surrogate مورد آزمایش قرار می‌گیرد |

### مقدار بازگشتی

True اگر کاراکترهای مشخص شده یک جفت surrogate را تشکیل دهند، در غیر این صورت - false

## متد Char::IsSurrogatePair(const String\&, int)


تعیین می‌کند که آیا دو کاراکتر متوالی در بافر کاراکتری مشخص شده یک جفت surrogate هستند یا خیر.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../string/)\& | یک رشته |
| index | int | شاخص صفر-مبنا در بافری که کاراکترها در آن قرار دارند و توالی کاراکتری که باید تست شود از اینجا شروع می‌شود |

### مقدار بازگشتی

True اگر کاراکترهای مشخص شده یک جفت surrogate را تشکیل دهند، در غیر این صورت - false

## موارد مرتبط

* کلاس [Char](../)
* کلاس [String](../../string/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)