---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته است را به عدد صحیح ۶۴ بیتی امضا‌شدهٔ معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/int64/parse/
---
## Int64::Parse(const String\&) متد


رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته است را به عدد صحیح ۶۴ بیتی امضا‌شدهٔ معادل تبدیل می‌کند.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشتی

عدد صحیح ۶۴ بیتی امضا‌شدهٔ برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده شده است.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد


رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته است را با استفاده از اطلاعات قالب‌بندی فراهم‌شده به عدد صحیح ۶۴ بیتی امضا‌شدهٔ معادل تبدیل می‌کند.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را دربر دارد. |

### مقدار بازگشتی

عدد صحیح ۶۴ بیتی امضا‌شدهٔ برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده شده است.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) متد




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد


رشتهٔ مشخص‌شده که حاوی نمایش عددی به صورت رشته است را با استفاده از اطلاعات قالب‌بندی و سبک عددی فراهم‌شده به عدد صحیح ۶۴ بیتی امضا‌شدهٔ معادل تبدیل می‌کند.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارندهٔ NumberStyles که سبک مجاز نمایش عددی را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را دربر دارد. |

### مقدار بازگشتی

عدد صحیح ۶۴ بیتی امضا‌شدهٔ برابر با عددی که توسط رشتهٔ مشخص‌شده نمایش داده شده است.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## مراجع

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)