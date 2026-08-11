---
title: Parse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که شامل نمایهٔ متنی عدد است را به عدد صحیح 32 بیتی معادل تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system/int32/parse/
---
## Int32::Parse(const String\&) متد

رشتهٔ مشخص‌شده که شامل نمایهٔ متنی عدد است را به عدد صحیح 32 بیتی معادل تبدیل می‌کند.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |

### مقدار بازگشتی

عدد صحیح 32 بیتی معادل عددی که توسط رشتهٔ مشخص‌شده نمایانده شده است.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که شامل نمایهٔ متنی عدد است را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به عدد صحیح 32 بیتی معادل تبدیل می‌کند.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که شامل اطلاعات فرمت رشته است. |

### مقدار بازگشتی

عدد صحیح 32 بیتی معادل عددی که توسط رشتهٔ مشخص‌شده نمایانده شده است.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) متد




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشتهٔ مشخص‌شده که شامل نمایهٔ متنی عدد است را با استفاده از اطلاعات قالب‌بندی و استایل عددی ارائه‌شده به عدد صحیح 32 بیتی معادل تبدیل می‌کند.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارنده NumberStyles که استایل مجاز نمایهٔ متنی عدد را مشخص می‌کند. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | یک اشاره‌گر به شیئی که شامل اطلاعات فرمت رشته است. |

### مقدار بازگشتی

عدد صحیح 32 بیتی معادل عددی که توسط رشتهٔ مشخص‌شده نمایانده شده است.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) متد




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) متد




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## مراجع مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Int32](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [CultureInfo](../../../system.globalization/cultureinfo/)
* کلاس [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* کلاس [ReadOnlySpan](../../readonlyspan/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)