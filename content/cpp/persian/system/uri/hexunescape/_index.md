---
title: HexUnescape()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش شش‌هشتگی مشخص‌شدهٔ یک کاراکتر را به کاراکتر تبدیل می‌کند.
type: docs
weight: 443
url: /fa/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) method

نمایش شش‌هشتگی مشخص شدهٔ یک کاراکتر را به یک کاراکتر تبدیل می‌کند.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | رشته‌ای شامل نمایش شش‌هشتگی یک کاراکتر |
| index | **int32_t**\& | موقعیتی در **pattern** که نمایش شش‌هشتگی کاراکتر از آن شروع می‌شود |

### مقدار بازگشت

کاراکتر نمایان‌ساز کدگذاری شش‌هشتگی در موقعیت **index**. اگر کاراکتر در **index** به صورت شش‌هشتگی کدگذاری نشده باشد، همان کاراکتر در **index** برگردانده می‌شود. مقدار **index** یک واحد افزایش می‌یابد تا به کاراکتر بعد از کاراکتر بازگردانده‌شده اشاره کند.

## موارد مرتبط

* کلاس [String](../../string/)
* کلاس [Uri](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)