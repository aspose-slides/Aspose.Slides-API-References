---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۸-بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/byte/parse/
---
## Byte::Parse(const String\&) متد

رشتهٔ مشخص شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۸-بیتی معادل تبدیل می‌کند.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشت

عدد صحیح بدون علامت ۸-بیتی که برابر عدد نمایان‌سازی شده در رشتهٔ مشخص شده است.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۸-بیتی معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی فراهم‌شده.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |

### مقدار بازگشت

عدد صحیح بدون علامت ۸-بیتی که برابر عدد نمایان‌سازی شده در رشتهٔ مشخص شده است.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص شده که شامل نمایش رشته‌ای یک عدد است را به عدد صحیح بدون علامت ۸-بیتی معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی فراهم‌شده و سبک عددی.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایش رشته‌ای عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود. |

### مقدار بازگشت

عدد صحیح بدون علامت ۸-بیتی که برابر عدد نمایان‌سازی شده در رشتهٔ مشخص شده است.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Byte](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)