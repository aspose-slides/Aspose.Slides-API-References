---
title: TryParseExact()
second_title: Aspose.Slides برای C++ مرجع API
description: سعی می‌کند رشتهٔ مشخص‌شده را با استفاده از قالب‌های مشخص، ارائه‌کنندهٔ قالب و سبک قالب‌بندی، به شیء DateTimeOffset تبدیل کند.
type: docs
weight: 742
url: /fa/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) متد

سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](../) با استفاده از قالب‌های مشخص، ارائه‌کنندهٔ قالب و سبک قالب‌بندی تبدیل کند.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | آرایه‌ای از رشته‌های قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کنندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) که معادل **input** است. |

### مقدار بازگشت

true اگر **input** با موفقیت تبدیل شد، در غیر این صورت false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) متد

سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](../) با استفاده از قالب، ارائه‌کنندهٔ قالب و سبک قالب‌بندی تبدیل کند.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| format | const [String](../../string/)\& | رشتهٔ قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کنندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) که معادل **input** است. |

### مقدار بازگشت

true اگر **input** با موفقیت تبدیل شد، در غیر این صورت false.

## موارد مرتبط

* شمارش [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعریف‌نوع [ArrayPtr](../../arrayptr/)
* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [DateTimeOffset](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)