---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که شامل نمایش عددی به صورت رشته است را به عدد صحیح ۳۲-بیتی علامت‌دار معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) متد


رشتهٔ مشخص شده که شامل نمایش عددی به صورت رشته است را به عدد صحیح ۳۲-بیتی علامت‌دار معادل تبدیل می‌کند.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **int32_t**\& | مرجع به متغیری از نوع عدد صحیح ۳۲-بیتی علامت‌دار که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگردانی

True اگر تبدیل موفق شد، در غیر این صورت - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) متد


رشتهٔ مشخص شده که شامل نمایش عددی به صورت رشته است را به عدد صحیح ۳۲-بیتی علامت‌دار معادل تبدیل می‌کند، با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه شده.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارندهٔ NumberStyles که سبک مجاز نمایش عددی را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |
| result | **int32_t**\& | مرجع به متغیری از نوع عدد صحیح ۳۲-بیتی علامت‌دار که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگردانی

True اگر تبدیل موفق شد، در غیر این صورت - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) متد




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) متد




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) متد




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)