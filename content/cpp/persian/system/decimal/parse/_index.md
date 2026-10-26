---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش رشته‌ای از یک عدد اعشاری را به یک نمونهٔ معادل از کلاس Decimal تبدیل می‌کند.
type: docs
weight: 469
url: /fa/system/decimal/parse/
---
## Decimal::Parse(const String\&) متد

نمایش رشته‌ای از یک عدد اعشاری را به یک نمونهٔ معادل از کلاس [Decimal](../) تبدیل می‌کند.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک عدد |

### مقدار بازگشتی

یک نمونهٔ جدید از کلاس [Decimal](../) که نمایانگر مقداری معادل مقدار نمایش داده شده توسط رشتهٔ مشخص‌شده است.

## Decimal::Parse(const String\&, Globalization::NumberStyles) متد

نمایش رشته‌ای از یک عدد اعشاری را با استفاده از سبک مشخص‌شده به یک نمونهٔ معادل از کلاس [Decimal](../) تبدیل می‌کند.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک مقدار اعشاری برای تبدیل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارش که اطلاعات اضافی دربارهٔ **s**، دربارهٔ عناصر سبک که ممکن است در **s** وجود داشته باشند، یا دربارهٔ تبدیل **s** به شیء [Decimal](../) فراهم می‌کند |

### مقدار بازگشتی

یک نمونهٔ جدید از کلاس [Decimal](../) که نمایانگر مقداری معادل مقدار نمایش داده شده توسط رشتهٔ مشخص‌شده است.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

نمایش رشته‌ای از یک عدد اعشاری را با استفاده از فراهم‌کنندهٔ قالب‌بندی مشخص‌شده به یک نمونهٔ معادل از کلاس [Decimal](../) تبدیل می‌کند.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک مقدار اعشاری برای تبدیل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | فراهم‌کنندهٔ قالب‌بندی |

### مقدار بازگشتی

یک نمونهٔ جدید از کلاس [Decimal](../) که نمایانگر مقداری معادل مقدار نمایش داده شده توسط رشتهٔ مشخص‌شده است.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

نمایش رشته‌ای از یک عدد اعشاری را با استفاده از سبک و فراهم‌کنندهٔ قالب‌بندی مشخص‌شده به یک نمونهٔ معادل از کلاس [Decimal](../) تبدیل می‌کند.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../string/)\& | نمایش رشته‌ای یک مقدار اعشاری برای تبدیل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارش که اطلاعات اضافی دربارهٔ **s**، دربارهٔ عناصر سبک که ممکن است در **s** وجود داشته باشند، یا دربارهٔ تبدیل **s** به شیء [Decimal](../) فراهم می‌کند |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | فراهم‌کنندهٔ قالب‌بندی |

### مقدار بازگشتی

یک نمونهٔ جدید از کلاس [Decimal](../) که نمایانگر مقداری معادل مقدار نمایش داده شده توسط رشتهٔ مشخص‌شده است.

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)