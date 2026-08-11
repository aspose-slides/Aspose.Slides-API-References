---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایش رشته‌ای مشخص از یک مقدار تاریخ و زمان را به شیء DateTime معادل تبدیل می‌کند.
type: docs
weight: 885
url: /fa/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) متد


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از یک مقدار تاریخ و زمان برای تبدیل. |
| result | [DateTime](../)\& | آرگومان خروجی که در صورت موفقیت تبدیل، شامل نتیجه تبدیل است. |

### مقدار بازگشتی

اگر تبدیل موفق باشد True، در غیر این صورت - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) متد


Converts the specified string representation of a date and time value to the equivalent [DateTime](../) object using the specified culture-specific format information and style.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از یک مقدار تاریخ و زمان برای تبدیل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات قالب‌بندی مخصوص فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | ترکیب بیتی مقادیر شمارشی که اطلاعات اضافی درباره **s**، درباره عناصر سبک موجود در **s** یا درباره تبدیل از **s** به شیء [DateTime](../) فراهم می‌آورد. |
| result | [DateTime](../)\& | آرگومان خروجی که در صورت موفقیت تبدیل، شامل نتیجه تبدیل است. |

### مقدار بازگشتی

اگر تبدیل موفق باشد True، در غیر این صورت - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) متد




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) متد




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) متد




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## مراجع

* شمارش [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعریف نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [DateTime](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)