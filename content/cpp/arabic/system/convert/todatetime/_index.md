---
title: ToDateTime()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: التحويل غير مدعوم. دائمًا يطرح InvalidCastException.
type: docs
weight: 248
url: /ar/system/convert/todatetime/
---
## Convert::ToDateTime(bool) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) طريقة

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) طريقة

يرجع التاريخ والوقت المحددين.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) طريقة

يقوم بتحويل السلسلة المحددة إلى نسخة من الفئة [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها |

### قيمة الإرجاع

نسخة من الفئة [DateTime](../../datetime/) تمثل معلومات التاريخ والوقت التي تمثلها السلسلة المحددة

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة إلى نسخة من الفئة [DateTime](../../datetime/) باستخدام معلومات التنسيق المقدمة.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

نسخة من الفئة [DateTime](../../datetime/) تمثل معلومات التاريخ والوقت التي تمثلها السلسلة المحددة

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) طريقة




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) طريقة




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل القيمة المغلفة المحددة إلى قيمة [DateTime](../../datetime/) مكافئة.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | المؤشر المشترك إلى الكائن الذي يعبئ القيمة المراد تحويلها |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة الذي سيُستخدم إذا كان نوع القيمة المغلفة هو [String](../../string/) |

### قيمة الإرجاع

قيمة [DateTime](../../datetime/) مكافئة للقيمة المغلفة المحددة

## راجع أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)