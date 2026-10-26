---
title: TryParseExact()
second_title: مرجع API Aspose.Slides برای C++
description: رشته را به شیء TimeSpan معادل با استفاده از قالب‌های مشخص‌شده و ارائه‌کننده قالب تبدیل می‌کند و نتیجهٔ تبدیل را برمی‌گرداند.
type: docs
weight: 573
url: /fa/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) متد

رشته را به شیء [TimeSpan](../) معادل با استفاده از قالب‌های مشخص‌شده و ارائه‌کننده قالب تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) از رشته‌های قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کننده قالب که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |
| result | [TimeSpan](../)\& | فاصله زمانی که با رشته مطابقت دارد. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شد true؛ در غیر این صورت false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

رشته را به شیء [TimeSpan](../) معادل با استفاده از قالب مشخص‌شده، ارائه‌کننده قالب و سبک‌ها تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| format | const [String](../../string/)\& | رشته قالب استاندارد یا سفارشی. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کننده قالب که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | عناصری که ممکن است در رشته ورودی حضور داشته باشند را تعریف می‌کند. |
| result | [TimeSpan](../)\& | فاصله زمانی که با رشته مطابقت دارد. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شد true؛ در غیر این صورت false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

رشته را به شیء [TimeSpan](../) معادل با استفاده از قالب‌های مشخص‌شده، ارائه‌کننده قالب و سبک‌ها تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) از رشته‌های قالب. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کننده قالب که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | عناصری که ممکن است در رشته ورودی حضور داشته باشند را تعریف می‌کند. |
| result | [TimeSpan](../)\& | فاصله زمانی که با رشته مطابقت دارد. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شد true؛ در غیر این صورت false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) متد

رشته را به شیء [TimeSpan](../) معادل با استفاده از قالب مشخص‌شده و ارائه‌کننده قالب تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| format | const [String](../../string/)\& | رشته قالب استاندارد یا سفارشی. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌کننده قالب که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |
| result | [TimeSpan](../)\& | فاصله زمانی که با رشته مطابقت دارد. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شد true؛ در غیر این صورت false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) متد

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## مراجع

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [TimeSpan](../)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)