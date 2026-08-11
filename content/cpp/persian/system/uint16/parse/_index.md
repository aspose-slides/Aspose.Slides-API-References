---
title: Parse()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده‌ای که نمایانگر عددی است را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/uint16/parse/
---
## UInt16::Parse(const String\&) متد

رشتهٔ مشخص‌شده‌ای که نمایانگر عددی است را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشت

عدد صحیح بدون علامت 16-بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایانده می‌شود.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده‌ای که نمایانگر عددی است را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی ارائه‌شده.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب رشته را شامل می‌شود. |

### مقدار بازگشت

عدد صحیح بدون علامت 16-بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایانده می‌شود.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده‌ای که نمایانگر عددی است را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارندهٔ NumberStyles که سبک مجاز نمایش عدد در رشته را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب رشته را شامل می‌شود. |

### مقدار بازگشت

عدد صحیح بدون علامت 16-بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایانده می‌شود.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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