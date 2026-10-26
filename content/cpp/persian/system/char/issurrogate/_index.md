---
title: IsSurrogate()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند آیا کاراکتر مشخص‌شده یک واحد کد سرگروه UTF-16 است یا خیر.
type: docs
weight: 14
url: /fa/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) متد


Determines if the specified character is a UTF-16 surrogate code unit.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| c | char_t | یک کاراکتر |

### مقدار بازگشت

True اگر کاراکتر مشخص‌شده یک واحد کد UTF-16 سرگروه باشد، در غیر این صورت - false

## Char::IsSurrogate(const String\&, int) متد


Determines whether the character at the specified index in the specified string is UTF-16 surrogate code unit.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | یک رشته |
| index | int | اندیس کاراکتر در رشتهٔ مشخص شده |

### مقدار بازگشت

True اگر کاراکتر در ایندکس مشخص‌شده یک واحد کد UTF-16 سرگروه باشد، در غیر این صورت - false

## موارد مرتبط

* کلاس [Char](../)
* کلاس [String](../../string/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)