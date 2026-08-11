---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به مقدار نقطه‌اعشاری تک‌دقت معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به مقدار نقطه‌اعشاری تک‌دقت معادل تبدیل می‌کند.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **float**\& | مرجع به یک متغیر نقطه‌اعشاری تک‌دقت که نتیجه تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

در صورتی که تبدیل موفق شد، True؛ در غیر اینصورت - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) متد

رشتهٔ مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به مقدار نقطه‌اعشاری تک‌دقت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی فراهم‌شده و سبک عددی.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش عدد به صورت رشته‌ای را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که شامل اطلاعات قالب‌بندی رشته است. |
| result | **float**\& | مرجع به یک متغیر نقطه‌اعشاری تک‌دقت که نتیجه تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

در صورتی که تبدیل موفق شد، True؛ در غیر اینصورت - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) متد

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) متد

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) متد

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## مراجع

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* ساختار [Single](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)