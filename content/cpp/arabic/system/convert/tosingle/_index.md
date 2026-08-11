---
title: ToSingle()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل القيمة المنطقية المحددة إلى عدد عائم ذي دقة أحادية مكافئ.
type: docs
weight: 209
url: /ar/system/convert/tosingle/
---
## Convert::ToSingle(bool) طريقة

يقوم بتحويل القيمة المنطقية المحددة إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) طريقة

يقوم بتحويل العدد الصحيح غير الموقّع 8-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) طريقة

يقوم بتحويل العدد الصحيح الموقّع 8-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) طريقة

يقوم بتحويل العدد الصحيح غير الموقّع 16-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) طريقة

يقوم بتحويل العدد الصحيح الموقّع 16-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) طريقة

يقوم بتحويل العدد الصحيح غير الموقّع 32-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) طريقة

يقوم بتحويل العدد الصحيح الموقّع 32-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) طريقة

يقوم بتحويل العدد الصحيح غير الموقّع 64-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) طريقة

يقوم بتحويل العدد الصحيح الموقّع 64-بت المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) طريقة

يعيد الرقم float المحدد.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) طريقة

يقوم بتحويل الرقم المزدوج الدقة المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) طريقة

يقوم بتحويل العدد العشري المحدد إلى عدد عائم ذي دقة أحادية مكافئ.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) طريقة

التحويل غير مدعم. دائمًا يثير InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) طريقة

التحويل غير مدعم. دائمًا يثير InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) طريقة

يقوم بتحويل السلسلة الفارغة المحددة إلى القيمة العائمة ذات الدقة الأحادية المكافئة.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### قيمة الإرجاع

صفر.

## Convert::ToSingle(const char_t *) طريقة

يقوم بتحويل سلسلة C-String التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة العائمة ذات الدقة الأحادية المكافئة.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const char_t * | سلسلة C-String للتحويل |

### قيمة الإرجاع

القيمة العائمة ذات الدقة الأحادية المكافئة للعدد الممثل بواسطة السلسلة المحددة

## Convert::ToSingle(const String\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة العائمة ذات الدقة الأحادية المكافئة.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |

### قيمة الإرجاع

القيمة العائمة ذات الدقة الأحادية المكافئة للعدد الممثل بواسطة السلسلة المحددة

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة العائمة ذات الدقة الأحادية المكافئة باستخدام معلومات التنسيق المقدمة.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

القيمة العائمة ذات الدقة الأحادية المكافئة للعدد الممثل بواسطة السلسلة المحددة

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل رقمي لسلسلة إلى القيمة العائمة ذات الدقة الأحادية المكافئة باستخدام معلومات التنسيق والنمط الرقمي المقدمين.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة قيم NumberStyles التي تحدد النمط المسموح به لتمثيل السلسلة الرقمية |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

القيمة العائمة ذات الدقة الأحادية المكافئة للعدد الممثل بواسطة السلسلة المحددة

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل القيمة المعبأة المحددة إلى قيمة عائمة ذات دقة أحادية.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | مؤشر المشاركة إلى الكائن المعبأ الذي يحتوي على القيمة المراد تحويلها |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة المستخدم إذا كان نوع القيمة المعبأة هو [String](../../string/) |

### قيمة الإرجاع

قيمة عائمة ذات دقة أحادية مكافئة للقيمة المعبأة المحددة

## انظر أيضًا

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