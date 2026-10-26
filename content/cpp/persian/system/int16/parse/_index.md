---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که شامل نمایهٔ عدد به صورت رشته‌ای است را به عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/int16/parse/
---
## Int16::Parse(const String\&) متد

رشتهٔ مشخص‌شده که حاوی نمایهٔ عدد به صورت رشته‌ای است را به عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشت

عدد صحیح ۱۶ بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایان شده است.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که نمایهٔ عدد به صورت رشته‌ای را دارد را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که اطلاعات قالب‌بندی رشته را دربردارد. |

### مقدار بازگشت

عدد صحیح ۱۶ بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایان شده است.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) متد




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که حاوی نمایهٔ عدد به صورت رشته‌ای است را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایهٔ رشته‌ای عدد را تعیین می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که اطلاعات قالب‌بندی رشته را دربردارد. |

### مقدار بازگشت

عدد صحیح ۱۶ بیتی برابر با عددی که توسط رشتهٔ مشخص‌شده نمایان شده است.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد 




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Int16](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)