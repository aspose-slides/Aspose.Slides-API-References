---
title: ToChar()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.
type: docs
weight: 118
url: /ar/system/convert/tochar/
---
## Convert::ToChar(bool) طريقة

التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) طريقة

يقوم بتحويل عدد صحيح غير موقع 8-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) طريقة

يقوم بتحويل عدد صحيح موقع 8-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) طريقة

يقوم بتحويل عدد صحيح غير موقع 16-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) طريقة

يقوم بتحويل عدد صحيح موقع 16-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) طريقة

يقوم بتحويل عدد صحيح غير موقع 32-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) طريقة

يقوم بتحويل عدد صحيح موقع 32-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) طريقة

يقوم بتحويل عدد صحيح غير موقع 64-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) طريقة

يقوم بتحويل عدد صحيح موقع 64-بت محدد إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) طريقة

التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) طريقة

التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) طريقة

التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) طريقة

يرجع حرف يونيكود المحدد.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) طريقة

التحويل غير مدعوم. دائمًا يتم رمي استثناء InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) طريقة

يقوم بتحويل أول حرف وحيد في سلسلة الحرف C المحددة إلى قيمة char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const char_t * | سلسلة الحرف C للتحويل؛ من المتوقع أن تكون السلسلة بطول حرف واحد بالضبط. |

### قيمة الإرجاع

الحرف الأول والوحيد من سلسلة الحرف C المحددة إذا كانت بطول حرف واحد بالضبط، وإلا - 0

## Convert::ToChar(const String\&) طريقة

يقوم بتحويل أول حرف وحيد في السلسلة المحددة إلى قيمة char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل؛ من المتوقع أن تكون السلسلة بطول حرف واحد بالضبط |

### قيمة الإرجاع

الحرف الأول والوحيد من السلسلة المحددة إذا كانت بطول حرف واحد بالضبط، وإلا - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل أول حرف وحيد في السلسلة المحددة إلى قيمة char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة للتحويل؛ من المتوقع أن تكون السلسلة بطول حرف واحد بالضبط |

### قيمة الإرجاع

الحرف الأول والوحيد من السلسلة المحددة إذا كانت بطول حرف واحد بالضبط، وإلا - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل القيمة المعلبة المحددة إلى حرف يونيكود مكافئ.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | مؤشر المشاركة إلى الكائن المعلب الذي يحتوي على القيمة للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة الذي سيُستخدم إذا كان نوع القيمة المعلبة هو [String](../../string/) |

### قيمة الإرجاع

حرف يونيكود مكافئ للقيمة المعلبة المحددة

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* فئة [Decimal](../../decimal/)
* فئة [DateTime](../../datetime/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [Object](../../object/)
* Struct [Convert](../)
* نطاق [System](../../)
* Library [Aspose.Slides](../../../)