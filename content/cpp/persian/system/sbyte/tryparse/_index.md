---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته است را به عدد صحیح ۸ بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته است را به عدد صحیح ۸ بیتی معادل تبدیل می‌کند.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **int8_t**\& | مرجع به متغیر عدد صحیح ۸ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته است را به عدد صحیح ۸ بیتی معادل تبدیل می‌کند و از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده استفاده می‌کند.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را در بر دارد. |
| result | **int8_t**\& | مرجع به متغیر عدد صحیح ۸ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) متد




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) متد




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) متد




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)