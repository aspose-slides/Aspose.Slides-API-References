---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: سعی می‌کند رشتهٔ مشخص‌شده را به شیء DateTimeOffset تبدیل کند.
type: docs
weight: 729
url: /fa/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) متد

سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](../) تبدیل کند.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) که برابر با **input** است. |

### مقدار بازگشت

true اگر **input** با موفقیت تبدیل شود، در غیر این صورت - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) متد

سعی می‌کند رشتهٔ مشخص‌شده را به شیء [DateTimeOffset](../) تبدیل کند با استفاده از ارائه‌دهندهٔ قالب مشخص‌شده و سبک قالب‌بندی.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) که برابر با **input** است. |

### مقدار بازگشت

true اگر **input** با موفقیت تبدیل شود، در غیر این صورت - false.

## مراجع

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)