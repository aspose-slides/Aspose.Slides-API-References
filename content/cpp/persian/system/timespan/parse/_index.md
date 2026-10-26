---
title: Parse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشته را به شیء TimeSpan معادل تبدیل می‌کند.
type: docs
weight: 534
url: /fa/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) متد

رشته را به شیء [TimeSpan](../) معادل تبدیل می‌کند.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |

### مقدار بازگشت

فاصله زمانی که به رشته مربوط می‌شود.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشته را با استفاده از ارائه‌دهنده قالب مشخص، به شیء [TimeSpan](../) معادل تبدیل می‌کند.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهنده قالب که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |

### مقدار بازگشت

فاصله زمانی که به رشته مربوط می‌شود.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد



```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) متد



```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) متد



```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## همچنین ببینید

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)