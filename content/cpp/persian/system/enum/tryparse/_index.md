---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: سعی می‌کند رشتهٔ مشخص‌شده را به ثابت معادل enum تبدیل کند.
type: docs
weight: 79
url: /fa/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) متد


سعی می‌کند رشتهٔ مشخص‌شده را به ثابت معادل enum تبدیل کند.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) که به‌عنوان شامل نام ثابت enum تفسیر می‌شود |
| result | E\& | پارامتر خروجی که در صورت موفقیت تبدیل، نتیجهٔ تبدیل را در تابع شامل می‌شود |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت - false

## Enum::TryParse(const String\&, bool, E\&) متد


سعی می‌کند رشتهٔ مشخص‌شده را به ثابت معادل enum تبدیل کند.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) که به‌عنوان شامل نام ثابت enum تفسیر می‌شود |
| ignoreCase | **bool** | مشخص می‌کند که آیا هنگام تفسیر رشته، به حروف حساس باشد |
| result | E\& | پارامتر خروجی که در صورت موفقیت تبدیل، نتیجهٔ تبدیل را در بازگشت تابع شامل می‌شود |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت - false

## مراجع

* کلاس [String](../../string/)
* ساختار [Enum](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)