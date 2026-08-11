---
title: ConvertToUtf32()
second_title: مرجع API Aspose.Slides برای C++
description: جفت سورروگیت UTF-16 مشخص‌شده را به واحد کد UTF-32 تبدیل می‌کند.
type: docs
weight: 287
url: /fa/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) متد

جفت سورروگیت UTF-16 مشخص‌شده را به واحد کد UTF-32 تبدیل می‌کند.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| highSurrogate | char_t | سورروگیت بالایی جفت سورروگیت UTF-16 برای تبدیل |
| lowSurrogate | char_t | سورروگیت پایینی جفت سورروگیت UTF-16 برای تبدیل |

### مقدار بازگشت

یک واحد کد UTF-32 حاصل از تبدیل

## Char::ConvertToUtf32(const String\&, int) متد

مقدار یک کاراکتر یا جفت سورروگیت کدگذاری‌شده به‌صورت UTF-16 در موقعیت مشخصی از یک رشته را به واحد کد UTF-32 تبدیل می‌کند.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | رشته‌ای که شامل یک کاراکتر یا جفت سورروگیت است |
| index | int | موقعیت شاخص کاراکتر یا جفت سورروگیت در رشتهٔ مشخص‌شده |

### مقدار بازگشت

یک واحد کد UTF-32 حاصل از تبدیل

## موارد مرتبط

* کلاس [Char](../)
* کلاس [String](../../string/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)