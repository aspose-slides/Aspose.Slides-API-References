---
title: ParseExact()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایش رشته‌ای مشخص از مقدار تاریخ و زمان را به شیء DateTime معادل تبدیل می‌کند با استفاده از قالب مشخص‌شده و اطلاعات قالب‌بندی مخصوص فرهنگ. قالب نمایش رشته باید دقیقاً با قالب مشخص‌شده مطابقت داشته باشد. اگر تبدیل شکست بخورد، یک استثنا پرتاب می‌شود.
type: docs
weight: 872
url: /fa/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


نمایش رشته‌ای مشخص از مقدار تاریخ و زمان را به شیء [DateTime](../) معادل تبدیل می‌کند با استفاده از قالب مشخص‌شده و اطلاعات قالب‌بندی مخصوص فرهنگ. قالب نمایش رشته باید دقیقاً با قالب مشخص‌شده مطابقت داشته باشد. اگر تبدیل شکست بخورد، یک استثنا پرتاب می‌شود.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از یک مقدار تاریخ و زمان برای تبدیل. |
| format | const [String](../../string/)\& | قالب رشته. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات قالب‌بندی مخصوص فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | ترکیبی بیتی از مقادیر شمارشی که اطلاعات اضافی درباره **s**، درباره عناصر سبک که ممکن است در **s** موجود باشند، یا درباره تبدیل **s** به شیء [DateTime](../) فراهم می‌کند. |

### مقدار بازگشت

یک نمونه جدید از کلاس [DateTime](../) که مقدار تاریخ و زمان معادل با مقداری که توسط رشته مشخص‌شده نمایان شده است را نشان می‌دهد.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


نمایش رشته‌ای مشخص از مقدار تاریخ و زمان را به شیء [DateTime](../) معادل تبدیل می‌کند با استفاده از قالب‌های مشخص‌شده، اطلاعات قالب‌بندی مخصوص فرهنگ و سبک. قالب نمایش رشته باید دقیقاً با یکی یا چند قالب مشخص‌شده مطابقت داشته باشد. اگر تبدیل شکست بخورد، یک استثنا پرتاب می‌شود.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای از یک مقدار تاریخ و زمان برای تبدیل. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | آرایه‌ای از قالب‌های رشته‌ای. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات قالب‌بندی مخصوص فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | ترکیبی بیتی از مقادیر شمارشی که اطلاعات اضافی درباره **s**، درباره عناصر سبک که ممکن است در **s** موجود باشند، یا درباره تبدیل **s** به شیء [DateTime](../) فراهم می‌کند. |

### مقدار بازگشت

یک نمونه جدید از کلاس [DateTime](../) که مقدار تاریخ و زمان معادل با مقداری که توسط رشته مشخص‌شده نمایان شده است را نشان می‌دهد.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## موارد مرتبط

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)