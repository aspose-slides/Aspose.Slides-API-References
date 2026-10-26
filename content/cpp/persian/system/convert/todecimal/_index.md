---
title: ToDecimal()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار بولی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.
type: docs
weight: 235
url: /fa/system/convert/todecimal/
---
## Convert::ToDecimal(bool) متد

عدد بولی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) متد

عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) متد

عدد صحیح دارای علامت ۸ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) متد

عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) متد

عدد صحیح دارای علامت ۱۶ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) متد

عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) متد

عدد صحیح دارای علامت ۳۲ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) متد

عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) متد

عدد صحیح دارای علامت ۶۴ بیتی مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) متد

عدد شناور (float) مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) متد

عدد دوبل (double) مشخص‌شده را به عدد اعشاری معادل تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) متد

عدد اعشاری مشخص‌شده را برمی‌گرداند.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) متد

رشته‌ null-مشخص‌شده را به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### مقدار بازگشت

صفر.

## Convert::ToDecimal(const char_t *) متد

c-string مشخص‌شده که نمایش عددی را دارا است به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const char_t * | c-stringی که باید تبدیل شود |

### مقدار بازگشت

مقدار [Decimal](../../decimal/) برابر با عددی که توسط c-string مشخص‌شده نمایان می‌شود

## Convert::ToDecimal(const String\&) متد

رشته مشخص‌شده که نمایش عددی را دارد به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |

### مقدار بازگشت

مقدار [Decimal](../../decimal/) برابر با عددی که توسط رشته مشخص‌شده نمایان می‌شود

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشته مشخص‌شده که نمایش عددی را دارد به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی فراهم‌شده.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که حاوی اطلاعات قالب رشته است |

### مقدار بازگشت

مقدار [Decimal](../../decimal/) برابر با عددی که توسط رشته مشخص‌شده نمایان می‌شود

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) متد

رشته مشخص‌شده که نمایش عددی را دارد به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند با استفاده از سبک‌های عددی و اطلاعات قالب‌بندی مشخص‌شده.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک‌های مجاز نمایان عددی را مشخص می‌کند |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که حاوی اطلاعات قالب رشته است |

### مقدار بازگشت

مقدار [Decimal](../../decimal/) برابر با عددی که توسط رشته مشخص‌شده نمایان می‌شود

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) متد

مقدار بسته‌بندی‌شدهٔ مشخص‌شده را به مقدار معادل [Decimal](../../decimal/) تبدیل می‌کند.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | اشاره‌گر مشترک به شیئی که مقدار بسته‌بندی‌شده برای تبدیل را در خود دارد |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | قالب رشته‌ای که در صورتی استفاده می‌شود که نوع مقدار بسته‌بندی‌شده [String](../../string/) باشد |

### مقدار بازگشت

مقدار [Decimal](../../decimal/) معادل مقدار بسته‌بندی‌شدهٔ مشخص‌شده

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)