---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده که نمایانگر عددی است را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) متد

رشتهٔ مشخص‌شده (String) که نمایانگر عددی است را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **uint8_t**\& | مرجع به متغیر عدد صحیح بدون علامت 8 بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

اگر تبدیل موفق شد True و در غیر این صورت false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) متد

رشتهٔ مشخص‌شده (String) که نمایانگر عددی است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده، به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیب بیتی مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |
| result | **uint8_t**\& | مرجع به متغیر عدد صحیح بدون علامت 8 بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

اگر تبدیل موفق شد True و در غیر این صورت false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) متد




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) متد




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) متد




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)