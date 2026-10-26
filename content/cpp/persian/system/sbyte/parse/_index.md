---
title: Parse()
second_title: Aspose.Slides برای مرجع API C++
description: رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح امضا‌شدهٔ ۸-بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/sbyte/parse/
---
## SByte::Parse(const String\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح ۸-بیتی امضا‌شدهٔ معادل تبدیل می‌کند.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل. |

### Return Value

عدد صحیح ۸-بیتی امضا‌شده برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده می‌شود.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح ۸-بیتی امضا‌شدهٔ معادل با استفاده از اطلاعات قالب‌بندی ارائه‌شده تبدیل می‌کند.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که شامل اطلاعات قالب‌بندی رشته است. |

### Return Value

عدد صحیح ۸-بیتی امضا‌شده برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده می‌شود.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) متد




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح ۸-بیتی امضا‌شدهٔ معادل با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده تبدیل می‌کند.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیب بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که شامل اطلاعات قالب‌بندی رشته است. |

### Return Value

عدد صحیح ۸-بیتی امضا‌شده برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده می‌شود.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## See Also

* enum [NumberStyles](../../../system.globalization/numberstyles/)
* typedef [SharedPtr](../../sharedptr/)
* class [String](../../string/)
* class [IFormatProvider](../../iformatprovider/)
* class [CultureInfo](../../../system.globalization/cultureinfo/)
* class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* struct [SByte](../)
* namespace [System](../../)
* library [Aspose.Slides](../../../)