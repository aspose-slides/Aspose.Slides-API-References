---
title: ToBoolean()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار بولی مشخص شده را برمی‌گرداند.
type: docs
weight: 79
url: /fa/system/convert/toboolean/
---
## Convert::ToBoolean(bool) متد

مقدار بولی مشخص‌شده را باز می‌گرداند.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) متد

عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) متد

عدد صحیح علامت‌دار ۸ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) متد

عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) متد

عدد صحیح علامت‌دار ۱۶ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) متد

عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) متد

عدد صحیح علامت‌دار ۳۲ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) متد

عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) متد

عدد صحیح علامت‌دار ۶۴ بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) متد

عدد شناور مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) متد

عدد دوبل مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) متد

عدد اعشاری مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException پرتاب می‌شود.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) متد

تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException پرتاب می‌شود.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) متد

رشته Null-string مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### مقدار بازگشت

False.

## Convert::ToBoolean(const char_t *) متد

رشته c-string مشخص‌شده را به مقدار نوع bool تبدیل می‌کند.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const char_t * | رشته c-string برای تبدیل |

### مقدار بازگشت

True اگر رشته c-string برابر با "True" باشد و false اگر رشته c-string برابر با "False" باشد.

## Convert::ToBoolean(const String\&) متد

رشته مشخص‌شده را به مقدار نوع bool تبدیل می‌کند.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |

### مقدار بازگشت

True اگر رشته c-string برابر با "True" باشد و false اگر رشته برابر با "False" باشد.

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) متد

رشته مشخص‌شده را به مقدار نوع bool تبدیل می‌کند.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته برای تبدیل |

### مقدار بازگشت

True اگر رشته c-string برابر با "True" باشد و false اگر رشته برابر با "False" باشد.

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) متد

مقدار جعبه‌شده مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr به شیء حاوی مقدار برای تبدیل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | قالب رشته‌ای که در صورت اینکه نوع مقدار جعبه‌شده [String](../../string/) باشد استفاده می‌شود |

### مقدار بازگشت

یک مقدار بولی معادل مقدار جعبه‌شده مشخص‌شده

## موارد مرتبط

* typedef [SharedPtr](../../sharedptr/)
* کلاس [Decimal](../../decimal/)
* کلاس [DateTime](../../datetime/)
* کلاس [String](../../string/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [Object](../../object/)
* ساختار [Convert](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)