---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشته را به شیء TimeSpan معادل تبدیل می‌کند و نتیجهٔ تبدیل را برمی‌گرداند.
type: docs
weight: 560
url: /fa/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) method

رشته را به شیء [TimeSpan](../) معادل تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| result | [TimeSpan](../)\& | بازه زمانی که به رشته مربوط می‌شود. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شود مقدار true؛ در غیر این صورت false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method

رشته را به شیء [TimeSpan](../) معادل با استفاده از ارائه‌دهنده قالب‌بندی مشخص تبدیل می‌کند و نتیجه تبدیل را برمی‌گرداند.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [String](../../string/)\& | رشته ورودی. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهنده قالب‌بندی که اطلاعات قالب‌بندی خاص فرهنگ را فراهم می‌کند. |
| result | [TimeSpan](../)\& | بازه زمانی که به رشته مربوط می‌شود. |

### مقدار بازگشت

در صورتی که رشته با موفقیت تبدیل شود مقدار true؛ در غیر این صورت false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) method

```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [TimeSpan](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)