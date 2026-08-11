---
title: IsHighSurrogate()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا کاراکتر در اندیس مشخص‌شدهٔ رشتهٔ مشخص‌شده، یک واحد کد UTF-16 high surrogate است.
type: docs
weight: 40
url: /fa/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) متد

مشخص می‌کند که آیا کاراکتر در اندیس مشخص‌شدهٔ رشتهٔ مشخص‌شده، یک واحد کد UTF-16 high surrogate است.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | یک رشته |
| index | int | اندیس کاراکتری که باید آزمون شود در رشتهٔ مشخص‌شده |

### مقدار بازگشت

در صورتی که کاراکتر در اندیس مشخص‌شده یک واحد کد UTF-16 high surrogate باشد، مقدار true برگردانده می‌شود؛ در غیر این صورت false

## Char::IsHighSurrogate(const char_t *, int) متد

مشخص می‌کند که آیا کاراکتر در اندیس مشخص‌شده در بافر کاراکتری مشخص‌شده، یک high surrogate است.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | اشاره‌گر به ابتدای بافر کاراکتر |
| idx | int | یک اندیس صفرآغاز در بافر مشخص‌شده برای کاراکتری که باید آزمون شود |

### مقدار بازگشت

در صورتی که کاراکتر در اندیس مشخص‌شده یک high surrogate باشد، مقدار true برگردانده می‌شود؛ در غیر این صورت false

## Char::IsHighSurrogate(char_t) متد

مشخص می‌کند که آیا کاراکتر مشخص‌شده یک high surrogate است.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | کاراکتری که باید آزمون شود |

### مقدار بازگشت

در صورتی که کاراکتر مشخص‌شده یک high surrogate باشد، مقدار true برگردانده می‌شود؛ در غیر این صورت false

## موارد مرتبط

* کلاس [String](../../string/)
* کلاس [Char](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)