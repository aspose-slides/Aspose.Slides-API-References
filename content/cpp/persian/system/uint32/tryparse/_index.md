---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده که شامل نمایهٔ متنی یک عدد است را به عدد صحیح بدون علامت ۳۲ بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method

رشتهٔ مشخص‌شده که شامل نمایهٔ متنی یک عدد است را به عدد صحیح بدون علامت ۳۲ بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **uint32_t**\& | مرجع به یک متغیر عدد صحیح بدون علامت ۳۲ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار برگشتی

True اگر تبدیل موفق باشد، در غیر این صورت false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method

رشتهٔ مشخص‌شده که شامل نمایهٔ متنی یک عدد است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به عدد صحیح بدون علامت ۳۲ بیتی معادل تبدیل می‌کند.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایهٔ متنی عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شی‌ای که اطلاعات قالب‌بندی رشته را دارا است. |
| result | **uint32_t**\& | مرجع به یک متغیر عدد صحیح بدون علامت ۳۲ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار برگشتی

True اگر تبدیل موفق باشد، در غیر این صورت false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## موارد مرتبط

* enum [NumberStyles](../../../system.globalization/numberstyles/)
* typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* ساختار [UInt32](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)