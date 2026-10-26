---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش رشته‌ای مشخص‌شده از مقدار تاریخ و زمان را به شیء DateTime معادل تبدیل می‌کند.
type: docs
weight: 859
url: /fa/system/datetime/parse/
---
## DateTime::Parse(const String\&) متد


نمایش رشته‌ای مشخص‌شده از مقدار تاریخ و زمان را به شیء [DateTime](../) معادل تبدیل می‌کند.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک مقدار تاریخ و زمان برای تبدیل. |

### مقدار بازگشت

نمونه جدیدی از کلاس [DateTime](../) که مقدار تاریخ و زمان معادل با مقداری که در رشته مشخص شده است را نشان می‌دهد.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) متد


نمایش رشته‌ای مشخص‌شده از مقدار تاریخ و زمان را به شیء [DateTime](../) معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی ویژه فرهنگ.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک مقدار تاریخ و زمان برای تبدیل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | شیء [IFormatProvider](../../iformatprovider/) که اطلاعات قالب‌بندی ویژه فرهنگ را فراهم می‌کند. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | یک ترکیب بیتی از مقادیر شمارشی که اطلاعات اضافی درباره **s**، درباره عناصر سبک که ممکن است در **s** حضور داشته باشند، یا درباره تبدیل **s** به شیء [DateTime](../) فراهم می‌کند. |

### مقدار بازگشت

نمونه جدیدی از کلاس [DateTime](../) که مقدار تاریخ و زمان معادل با مقداری که در رشته مشخص شده است را نشان می‌دهد.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) متد




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) متد




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) متد




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## موارد مرتبط

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [DateTime](../)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)