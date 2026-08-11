---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت 16 بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) متد

رشتهٔ مشخص‌شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت 16 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **uint16_t**\& | مرجع به یک متغیر عدد صحیح بدون علامت 16 بیتی که نتیجه تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشتی

True اگر تبدیل موفق باشد، در غیر اینصورت - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) متد

رشتهٔ مشخص‌شده که شامل نمایش رشته‌ای یک عدد است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده، به عدد صحیح بدون علامت 16 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |
| result | **uint16_t**\& | مرجع به یک متغیر عدد صحیح بدون علامت 16 بیتی که نتیجه تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشتی

True اگر تبدیل موفق باشد، در غیر اینصورت - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) متد

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) متد

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) متد

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)