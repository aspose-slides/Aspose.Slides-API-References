---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که نمایانگر یک عدد است را به مقدار معادل نقطه شناور دوبل دقت تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/double/parse/
---
## Double::Parse(const String\&) متد

رشتهٔ مشخص شده که نمایانگر یک عدد است را به مقدار معادل نقطه شناور دوبل دقت تبدیل می‌کند.

```cpp
static double System::Double::Parse(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشتی

مقدار نقطه شناور دوبل دقت برابر با عددی که توسط رشتهٔ مشخص شده نمایانده شده است.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص شده که نمایانگر یک عدد است را با استفاده از اطلاعات قالب‌بندی فراهم‌شده به مقدار معادل نقطه شناور دوبل دقت تبدیل می‌کند.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | نشانگری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |

### مقدار بازگشتی

مقدار نقطه شناور دوبل دقت برابر با عددی که توسط رشتهٔ مشخص شده نمایانده شده است.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) متد

```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص شده که نمایانگر یک عدد است را با استفاده از اطلاعات قالب‌بندی فراهم‌شده و سبک عددی، به مقدار معادل نقطه شناور دوبل دقت تبدیل می‌کند.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | نشانگری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |

### مقدار بازگشتی

مقدار نقطه شناور دوبل دقت برابر با عددی که توسط رشتهٔ مشخص شده نمایانده شده است.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## مراجع

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)