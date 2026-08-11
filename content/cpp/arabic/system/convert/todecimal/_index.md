---
title: ToDecimal()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل القيمة البوليانية المحددة إلى رقم عشري مكافئ.
type: docs
weight: 235
url: /ar/system/convert/todecimal/
---
## طريقة Convert::ToDecimal(bool)

تحول القيمة البوليانية المحددة إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## طريقة Convert::ToDecimal(uint8_t)

تحول العدد الصحيح غير الموقّع 8-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## طريقة Convert::ToDecimal(int8_t)

تحول العدد الصحيح الموقع 8-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## طريقة Convert::ToDecimal(uint16_t)

تحول العدد الصحيح غير الموقّع 16-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## طريقة Convert::ToDecimal(int16_t)

تحول العدد الصحيح الموقع 16-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## طريقة Convert::ToDecimal(uint32_t)

تحول العدد الصحيح غير الموقّع 32-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## طريقة Convert::ToDecimal(int32_t)

تحول العدد الصحيح الموقع 32-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## طريقة Convert::ToDecimal(uint64_t)

تحول العدد الصحيح غير الموقّع 64-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## طريقة Convert::ToDecimal(int64_t)

تحول العدد الصحيح الموقع 64-بت المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## طريقة Convert::ToDecimal(float)

تحول العدد العائم المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## طريقة Convert::ToDecimal(double)

تحول العدد المزدوج المحدد إلى رقم عشري مكافئ.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## طريقة Convert::ToDecimal(const Decimal\&)

تُرجع الرقم العشري المحدد.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## طريقة Convert::ToDecimal(char_t)

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## طريقة Convert::ToDecimal(DateTime)

التحويل غير مدعوم. دائمًا يطرح InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## طريقة Convert::ToDecimal(std::nullptr_t)

تحول السلسلة الفارغة المحددة إلى القيمة المكافئة [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### قيمة الإرجاع

صفر.

## طريقة Convert::ToDecimal(const char_t *) 

تحول السلسلة c-string المحددة التي تحتوي على تمثيل رقمي إلى القيمة المكافئة [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const char_t * | السلسلة c-string للتحويل |

### قيمة الإرجاع

القيمة [Decimal](../../decimal/) التي تساوي الرقم المُمَثَّل بالسلسلة المحددة

## طريقة Convert::ToDecimal(const String\&)

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي إلى القيمة المكافئة [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |

### قيمة الإرجاع

القيمة [Decimal](../../decimal/) التي تساوي الرقم المُمَثَّل بالسلسلة المحددة

## طريقة Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&)

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي إلى القيمة المكافئة [Decimal](../../decimal/) باستخدام معلومات التنسيق المقدمة.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

القيمة [Decimal](../../decimal/) التي تساوي الرقم المُمَثَّل بالسلسلة المحددة

## طريقة Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&)

تحول السلسلة المحددة التي تحتوي على تمثيل رقمي إلى القيمة المكافئة [Decimal](../../decimal/) باستخدام أنماط الأعداد المحددة ومعلومات التنسيق.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم تعداد NumberStyles يحدد النمط المسموح به لتمثيل الرقم |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |

### قيمة الإرجاع

القيمة [Decimal](../../decimal/) التي تساوي الرقم المُمَثَّل بالسلسلة المحددة

## طريقة Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&)

تحول القيمة المغلّفة المحددة إلى القيمة المكافئة [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | المؤشر المشترك إلى الكائن الذي يغلف القيمة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة الذي سيُستخدم إذا كان نوع القيمة المغلّفة هو [String](../../string/) |

### قيمة الإرجاع

قيمة [Decimal](../../decimal/) مكافئة للقيمة المغلّفة المحددة

## انظر أيضًا

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