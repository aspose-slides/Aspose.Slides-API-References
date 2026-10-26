---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشته مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح علامت‌دار 16 بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) متد


رشته مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را به عدد صحیح علامت‌دار 16 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **int16_t**\& | مرجع به متغیر عدد صحیح علامت‌دار 16 بیتی که در آن نتیجه تبدیل قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق باشد، در غیر این صورت false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) متد


رشته مشخص‌شده که شامل نمایش عدد به صورت رشته‌ای است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده، به عدد صحیح علامت‌دار 16 بیتی معادل تبدیل می‌کند.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیب بیتی مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای یک عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب رشته را شامل می‌شود. |
| result | **int16_t**\& | مرجع به متغیر عدد صحیح علامت‌دار 16 بیتی که در آن نتیجه تبدیل قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق باشد، در غیر این صورت false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) متد




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) متد




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) متد




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## مراجع

* enum [NumberStyles](../../../system.globalization/numberstyles/)
* typedef [SharedPtr](../../sharedptr/)
* class [String](../../string/)
* class [Int16](../)
* class [IFormatProvider](../../iformatprovider/)
* class [CultureInfo](../../../system.globalization/cultureinfo/)
* class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* namespace [System](../../)
* library [Aspose.Slides](../../../)