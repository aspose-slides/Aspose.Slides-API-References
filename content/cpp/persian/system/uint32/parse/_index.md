---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که نمایانگر یک عدد است را به عدد صحیح ۳۲ بیتی بدون علامت معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/uint32/parse/
---
## UInt32::Parse(const String\&) متد

رشتهٔ مشخص‌شده که نمایانگر یک عدد است را به عدد صحیح ۳۲ بیتی بدون علامت معادل تبدیل می‌کند.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشتی

عدد صحیح ۳۲ بیتی بدون علامت برابر با عدد نمایان‌سازی شده در رشتهٔ مشخص‌شده.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که نمایانگر یک عدد است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به عدد صحیح ۳۲ بیتی بدون علامت معادل تبدیل می‌کند.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | نشانی به شیئی که شامل اطلاعات قالب‌بندی رشته است. |

### مقدار بازگشتی

عدد صحیح ۳۲ بیتی بدون علامت برابر با عدد نمایان‌سازی شده در رشتهٔ مشخص‌شده.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که نمایانگر یک عدد است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به عدد صحیح ۳۲ بیتی بدون علامت معادل تبدیل می‌کند.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیب بیتی مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | نشانی به شیئی که شامل اطلاعات قالب‌بندی رشته است. |

### مقدار بازگشتی

عدد صحیح ۳۲ بیتی بدون علامت برابر با عدد نمایان‌سازی شده در رشتهٔ مشخص‌شده.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)