---
title: ParseExact()
second_title: مرجع API Aspose.Slides برای C++
description: رشته را به شیء معادل TimeSpan با استفاده از فرمت‌های مشخص، ارائه‌کننده فرمت و سبک‌ها تبدیل می‌کند.
type: docs
weight: 547
url: /fa/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) متد

رشته را به شیء معادل [TimeSpan](../) با استفاده از فرمت‌های مشخص، ارائه‌دهنده فرمت و سبک‌ها تبدیل می‌کند.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) از رشته‌های فرمت. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهنده فرمت که اطلاعات قالب‌بندی مخصوص به فرهنگ را فراهم می‌کند. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | عناصر موجود در رشته ورودی را تعریف می‌کند. |

### مقدار بازگشتی

فاصله زمانی که با رشته مطابقت دارد.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) متد

رشته را به شیء معادل [TimeSpan](../) با استفاده از فرمت مشخص، ارائه‌دهنده فرمت و سبک‌ها تبدیل می‌کند.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| format | const [String](../../string/)\& | رشته فرمت استاندارد یا سفارشی. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهنده فرمت که اطلاعات قالب‌بندی مخصوص به فرهنگ را فراهم می‌کند. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | عناصر موجود در رشته ورودی را تعریف می‌کند. |

### مقدار بازگشتی

فاصله زمانی که با رشته مطابقت دارد.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) متد

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## موارد مرتبط

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [TimeSpan](../)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای نام [System](../../)
* Library [Aspose.Slides](../../../)