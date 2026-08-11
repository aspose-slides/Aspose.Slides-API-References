---
title: Parse()
second_title: Aspose.Slides برای مرجع API C++
description: رشتهٔ مشخص‌شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۶۴-بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/uint64/parse/
---
## UInt64::Parse(const String\&) متد

رشتهٔ مشخص‌شده که حاوی نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۶۴-بیتی معادل تبدیل می‌کند.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشت

عدد صحیح بدون علامت ۶۴-بیتی معادل عددی که در رشتهٔ مشخص‌شده نمایش داده شده است.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که حاوی نمایش رشته‌ای یک عدد است را با استفاده از اطلاعات قالب‌بندی فراهم‌شده به عدد صحیح بدون علامت ۶۴-بیتی معادل تبدیل می‌کند.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که حاوی اطلاعات قالب‌بندی رشته است. |

### مقدار بازگشت

عدد صحیح بدون علامت ۶۴-بیتی معادل عددی که در رشتهٔ مشخص‌شده نمایش داده شده است.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که حاوی نمایش رشته‌ای یک عدد است را با استفاده از اطلاعات قالب‌بندی و سبک عددی فراهم‌شده، به عدد صحیح بدون علامت ۶۴-بیتی معادل تبدیل می‌کند.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که حاوی اطلاعات قالب‌بندی رشته است. |

### مقدار بازگشت

عدد صحیح بدون علامت ۶۴-بیتی معادل عددی که در رشتهٔ مشخص‌شده نمایش داده شده است.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)