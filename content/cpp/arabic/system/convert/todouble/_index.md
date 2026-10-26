---
title: ToDouble()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحول القيمة المنطقية المحددة إلى عدد عائم مزدوج الدقة مكافئ.
type: docs
weight: 222
url: /ar/system/convert/todouble/
---
## Convert::ToDouble(bool) طريقة

تحول القيمة المنطقية المحددة إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) طريقة

تحول عدد صحيح غير موقع 8-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) طريقة

تحول عدد صحيح موقع 8-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) طريقة

تحول عدد صحيح غير موقع 16-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) طريقة

تحول عدد صحيح موقع 16-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) طريقة

تحول عدد صحيح غير موقع 32-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) طريقة

تحول عدد صحيح موقع 32-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) طريقة

تحول عدد صحيح غير موقع 64-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) طريقة

تحول عدد صحيح موقع 64-بت المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) طريقة

تحول العدد ذو الدقة الفردية المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) طريقة

يعيد العدد المزدوج المحدد.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) طريقة

تحول الرقم العشري المحدد إلى عدد عائم مزدوج الدقة مكافئ.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) طريقة

التحويل غير مدعوم. يرمي دائمًا استثناء InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) طريقة

التحويل غير مدعوم. يرمي دائمًا استثناء InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) طريقة

تحول السلسلة الفارغة المحددة إلى قيمة عدد عائم مزدوج الدقة مكافئ.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### قيمة الإرجاع

Zero.

## Convert::ToDouble(const char_t *) طريقة

تحول سلسلة C المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد عائم مزدوج الدقة مكافئة.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | سلسلة C للتحويل |

### قيمة الإرجاع

قيمة عدد عائم مزدوج الدقة مساوية للعدد الممثل بالسلسلة C المحددة

## Convert::ToDouble(const String\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد عائم مزدوج الدقة مكافئة.

```cpp
static double System::Convert::ToDouble(const String &value)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |

### قيمة الإرجاع

قيمة عدد عائم مزدوج الدقة مساوية للعدد الممثل بالسلسلة المحددة

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد عائم مزدوج الدقة مكافئة باستخدام معلومات التنسيق المقدَّمة.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

قيمة عدد عائم مزدوج الدقة مساوية للعدد الممثل بالسلسلة المحددة

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل نصي لعدد إلى قيمة عدد عائم مزدوج الدقة مكافئة باستخدام معلومات التنسيق المقدَّمة ونمط العدد.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة قيم تعداد NumberStyles تحدد النمط المسموح به لتمثيل النص للعدد |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

قيمة عدد عائم مزدوج الدقة مساوية للعدد الممثل بالسلسلة المحددة

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول القيمة المعلَّبة المحددة إلى قيمة عدد عائم مزدوج الدقة. إذا كان نوع القيمة المعلَّبة هو [String](../../string/)، يُستخدم تنسيق السلسلة المحدد أثناء التحويل.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | مؤشر المشاركة إلى الكائن الذي يعلّب القيمة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة الذي سيُستعمل إذا كان نوع القيمة المعلَّبة هو [String](../../string/) |

### قيمة الإرجاع

قيمة عدد عائم مزدوج الدقة مكافئة للقيمة المعلَّبة المحددة

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