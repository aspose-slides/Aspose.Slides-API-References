---
title: ToBoolean()
second_title: مرجع API Aspose.Slides للـ C++
description: تُرجِع القيمة المنطقية المحددة.
type: docs
weight: 79
url: /ar/system/convert/toboolean/
---
## Convert::ToBoolean(bool) طريقة


تُرجِع القيمة المنطقية المحددة.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) طريقة


تحول العدد الصحيح غير الموقّع 8-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) طريقة


تحول العدد الصحيح الموقّع 8-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) طريقة


تحول العدد الصحيح غير الموقّع 16-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) طريقة


تحول العدد الصحيح الموقّع 16-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) طريقة


تحول العدد الصحيح غير الموقّع 32-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) طريقة


تحول العدد الصحيح الموقّع 32-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) طريقة


تحول العدد الصحيح غير الموقّع 64-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) طريقة


تحول العدد الصحيح الموقّע 64-بت المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) طريقة


تحول العدد العائم المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) طريقة


تحول العدد المزدوج المحدد إلى قيمة منطقية مكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) طريقة


تحول العدد العشري المحدد إلى قيمة منطقية مكافئة.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) طريقة


التحويل غير مدعوم. دائمًا يُثير InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) طريقة


التحويل غير مدعوم. دائمًا يُثير InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) طريقة


تحول السلسلة الفارغة المحددة إلى القيمة المنطقية المكافئة.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### قيمة الإرجاع

خطأ.

## Convert::ToBoolean(const char_t *) طريقة


تحول السلسلة c-string المحددة إلى قيمة من نوع bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const char_t * | السلسلة c-string التي سيتم تحويلها |

### قيمة الإرجاع

صحيح إذا كان السلسلة c-string المحددة مساوية لـ "True" و خطأ إذا كان السلسلة c-string المحددة مساوية لـ "False".

## Convert::ToBoolean(const String\&) طريقة


تحول السلسلة المحددة إلى قيمة من نوع bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها |

### قيمة الإرجاع

صحيح إذا كان السلسلة c-string المحددة مساوية لـ "True" و خطأ إذا كان السلسلة المحددة مساوية لـ "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة


تحول السلسلة المحددة إلى قيمة من نوع bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها |

### قيمة الإرجاع

صحيح إذا كان السلسلة c-string المحددة مساوية لـ "True" و خطأ إذا كان السلسلة المحددة مساوية لـ "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) طريقة


تحول القيمة المغلفة المحددة إلى قيمة منطقية مكافئة.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | مؤشر المشاركة إلى الكائن الذي يغلف القيمة المطلوب تحويلها |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | تنسيق السلسلة الذي سيُستخدم إذا كان نوع القيمة المغلفة هو [String](../../string/) |

### قيمة الإرجاع

قيمة منطقية مكافئة للقيمة المغلفة المحددة

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)