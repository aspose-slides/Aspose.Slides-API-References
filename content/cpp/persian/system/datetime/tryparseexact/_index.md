---
title: TryParseExact()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش رشته‌ای مشخص شده از مقدار تاریخ و زمان را با استفاده از قالب مشخص شده، اطلاعات فرمت مربوط به فرهنگ و سبک، به شیء DateTime معادل تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با قالب مشخص شده مطابقت داشته باشد.
type: docs
weight: 898
url: /fa/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

نمایش رشته‌ای مشخص شده از مقدار تاریخ و زمان را با استفاده از قالب مشخص شده، اطلاعات فرمت مربوط به فرهنگ و سبک، به شیء [DateTime](../) معادل تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با قالب مشخص شده مطابقت داشته باشد.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از مقدار تاریخ و زمان برای تبدیل. |
| format | const [String](../../string/)\& | فرمت رشته‌ای. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات فرمت مربوط به فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | یک ترکیب بیتی از مقادیر enumeration که اطلاعات اضافی درباره **s**، درباره عناصر style که ممکن است در **s** وجود داشته باشند، یا درباره تبدیل **s** به یک شیء [DateTime](../) فراهم می‌کند. |
| result | [DateTime](../)\& | آرگومان خروجی که در صورت موفقیت تبدیل، شامل نتیجه تبدیل است. |

### Return Value

اگر تبدیل موفق باشد true، در غیر این صورت false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

نمایش رشته‌ای مشخص شده از مقدار تاریخ و زمان را با استفاده از قالب‌های مشخص شده، اطلاعات فرمت مربوط به فرهنگ و سبک، به شیء [DateTime](../) معادل تبدیل می‌کند. قالب نمایش رشته باید دقیقاً با یکی از قالب‌های مشخص شده مطابقت داشته باشد.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از مقدار تاریخ و زمان برای تبدیل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | آرایه‌ای از فرمت‌های رشته‌ای. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات فرمت مربوط به فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | یک ترکیب بیتی از مقادیر enumeration که اطلاعات اضافی درباره **s**، درباره عناصر style که ممکن است در **s** وجود داشته باشند، یا درباره تبدیل **s** به یک شیء [DateTime](../) فراهم می‌کند. |
| result | [DateTime](../)\& | آرگومان خروجی که در صورت موفقیت تبدیل، شامل نتیجه تبدیل است. |

### Return Value

اگر تبدیل موفق باشد true، در غیر این صورت false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## موارد مرتبط

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)