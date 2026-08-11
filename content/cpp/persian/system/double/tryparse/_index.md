---
title: TryParse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده که نمایش عدد به صورت رشته را دارد به مقدار معادل عدد شناور دو دقت تبدیل می‌کند.
type: docs
weight: 14
url: /fa/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) متد

رشتهٔ مشخص‌شده که نمایش عدد به صورت رشته را دارد به مقدار معادل عدد شناور دو دقت تبدیل می‌کند.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| result | **double**\& | اشاره‌گری به متغیر عدد شناور دو دقت که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

در صورت موفقیت تبدیل، true؛ در غیر این صورت - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) متد

رشتهٔ مشخص‌شده که نمایش عدد به صورت رشته را دارد به مقدار معادل عدد شناور دو دقت تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی فراهم‌شده و سبک عدد.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیب بیتی مقادیر enum NumberStyles که سبک مجاز نمایش عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که شامل اطلاعات قالب‌بندی رشته است. |
| result | **double**\& | اشاره‌گری به متغیر عدد شناور دو دقت که نتیجهٔ تبدیل در آن قرار می‌گیرد. |

### مقدار بازگشت

در صورت موفقیت تبدیل، true؛ در غیر این صورت - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) متد

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) متد

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) متد

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)