---
title: ToDouble()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار بولینی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.
type: docs
weight: 222
url: /fa/system/convert/todouble/
---
## Convert::ToDouble(bool) متد

عدد بولینی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```
## Convert::ToDouble(uint8_t) متد

عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```
## Convert::ToDouble(int8_t) متد

عدد صحیح علامتی ۸ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```
## Convert::ToDouble(uint16_t) متد

عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```
## Convert::ToDouble(int16_t) متد

عدد صحیح علامتی ۱۶ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```
## Convert::ToDouble(uint32_t) متد

عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```
## Convert::ToDouble(int32_t) متد

عدد صحیح علامتی ۳۲ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```
## Convert::ToDouble(uint64_t) متد

عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```
## Convert::ToDouble(int64_t) متد

عدد صحیح علامتی ۶۴ بیتی مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```
## Convert::ToDouble(float) متد

عدد دقیق تک‌دقت مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```
## Convert::ToDouble(double) متد

عدد شناور دوگانه‌دقت مشخص‌شده را برمی‌گرداند.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```
## Convert::ToDouble(const Decimal\&) متد

عدد اعشاری مشخص‌شده را به عدد شناور دوگانه‌دقت معادل تبدیل می‌کند.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```
## Convert::ToDouble(char_t) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند.

```cpp
static double System::Convert::ToDouble(char_t value)
```
## Convert::ToDouble(DateTime) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند.

```cpp
static double System::Convert::ToDouble(DateTime value)
```
## Convert::ToDouble(std::nullptr_t) متد

رشته‌ خالی (null-string) مشخص‌شده را به مقدار برابر عدد شناور دوگانه‌دقت تبدیل می‌کند.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### مقدار بازگشت

صفر.

## Convert::ToDouble(const char_t *) متد

رشته ‎c‎ حاوی نمایش عددی را به مقدار برابر عدد شناور دوگانه‌دقت تبدیل می‌کند.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | const char_t * | رشته ‎c‎ برای تبدیل |

### مقدار بازگشت

مقدار عدد شناور دوگانه‌دقت برابر با عددی که در رشته ‎c‎ مشخص‌شده نمایش داده شده است

## Convert::ToDouble(const String\&) متد

رشته حاوی نمایش عددی را به مقدار برابر عدد شناور دوگانه‌دقت تبدیل می‌کند.

```cpp
static double System::Convert::ToDouble(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |

### مقدار بازگشت

مقدار عدد شناور دوگانه‌دقت برابر با عددی که در رشته مشخص‌شده نمایش داده شده است

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشته حاوی نمایش عددی را به مقدار برابر عدد شناور دوگانه‌دقت تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی ارائه‌شده.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود |

### مقدار بازگشت

مقدار عدد شناور دوگانه‌دقت برابر با عددی که در رشته مشخص‌شده نمایش داده شده است

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) متد




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشته حاوی نمایش عددی را به مقدار برابر عدد شناور دوگانه‌دقت تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر شمارش‌گر NumberStyles که سبک مجاز نمایش عدد را مشخص می‌کند |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود |

### مقدار بازگشت

مقدار عدد شناور دوگانه‌دقت برابر با عددی که در رشته مشخص‌شده نمایش داده شده است

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) متد




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) متد




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) متد




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) متد

مقدار بسته‌بندی‌شده مشخص‌شده را به مقدار عدد شناور دوگانه‌دقت تبدیل می‌کند. اگر نوع مقدار بسته‌بندی‌شده [String](../../string/) باشد، قالب رشته‌ای مشخص‌شده در زمان تبدیل استفاده می‌شود.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | اشاره‌گر مشترک به شیئی که مقدار بسته‌بندی‌شده برای تبدیل را در خود دارد |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | قالب رشته‌ای که در صورت بودن نوع مقدار بسته‌بندی‌شده [String](../../string/) استفاده می‌شود |

### مقدار بازگشت

مقدار عدد شناور دوگانه‌دقت معادل مقدار بسته‌بندی‌شده مشخص‌شده

## مراجع

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)