---
title: ParseExact()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده را با استفاده از قالب، ارائه‌دهندهٔ قالب و سبک قالب‌بندی مشخص شده به شیء DateTimeOffset تبدیل می‌کند.
type: docs
weight: 716
url: /fa/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) متد

رشتهٔ مشخص‌شده را با استفاده از قالب، ارائه‌دهندهٔ قالب و سبک قالب‌بندی مشخص‌شده به شیء [DateTimeOffset](../) تبدیل می‌کند.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| format | const [String](../../string/)\& | رشتهٔ قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |

### مقدار بازگشت

[DateTimeOffset](../) که معادل **input** است.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) متد

رشتهٔ مشخص‌شده را با استفاده از قالب‌های مشخص‌شده، ارائه‌دهندهٔ قالب و سبک قالب‌بندی مشخص‌شده به شیء [DateTimeOffset](../) تبدیل می‌کند.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) برای تبدیل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) از رشته‌های قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهندهٔ قالب. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | سبک‌های قالب‌بندی تاریخ و زمان. |

### مقدار بازگشت

[DateTimeOffset](../) که معادل **input** است.

## مراجع مرتبط

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)