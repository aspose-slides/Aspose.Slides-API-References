---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده که حاوی نمایش متنی یک عدد است را به عدد صحیح بدون علامت 64-بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) متد

رشته مشخص‌شده حاوی نمایش متنی یک عدد را به عدد صحیح بدون علامت 64-بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای برای تبدیل. |
| result | **uint64_t**\& | مرجع به متغیر عدد صحیح بدون علامت 64-بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### Return Value

در صورتی که تبدیل موفق شود مقدار True برگردانده می‌شود، در غیر این صورت False.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) متد

رشته مشخص‌شده حاوی نمایش متنی یک عدد را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به عدد صحیح بدون علامت 64-بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای برای تبدیل. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enumeration NumberStyles که سبک مجاز نمایش متنی یک عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | نشان‌گری به شیئی که شامل اطلاعات قالب‌بندی رشته است. |
| result | **uint64_t**\& | مرجع به متغیر عدد صحیح بدون علامت 64-بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### Return Value

در صورتی که تبدیل موفق شود مقدار True برگردانده می‌شود، در غیر این صورت False.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) متد




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) متد




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) متد




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## مراجع

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)