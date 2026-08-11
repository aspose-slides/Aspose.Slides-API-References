---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده حاوی نمایش عددی را به عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/int64/tryparse/
---
## Int64::TryParse(const String&, int64_t&) متد


رشتهٔ مشخص‌شده حاوی نمایش عددی را به عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)& | رشته‌ای که باید تبدیل شود. |
| result | **int64_t**& | ارجاع به متغیر عدد صحیح ۶۴ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت false.

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>&, int64_t&) متد


رشتهٔ مشخص‌شده حاوی نمایش عددی را به عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند، با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش عددی را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | اشاره‌گری به شیئی که شامل اطلاعات قالب‌بندی رشته است. |
| result | **int64_t**& | ارجاع به متغیر عدد صحیح ۶۴ بیتی که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

True اگر تبدیل موفق شد، در غیر این صورت false.

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>&, int64_t&) متد




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>&, int64_t&) متد




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, int64_t&) متد




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)