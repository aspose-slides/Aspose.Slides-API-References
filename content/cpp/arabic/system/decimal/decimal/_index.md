---
title: Decimal()
second_title: Aspose.Slides للغة C++ مرجع API
description: ينشئ كائنًا يمثل 0.
type: docs
weight: 1
url: /ar/system/decimal/decimal/
---
## Decimal::Decimal() منشئ

ينشئ كائنًا يمثل 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::int8_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::int8_t | قيمة عدد صحيح 8-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::int16_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::int16_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::int16_t | قيمة عدد صحيح 16-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::int32_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::int32_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::int32_t | قيمة عدد صحيح 32-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::int64_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::int64_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::int64_t | قيمة عدد صحيح 64-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::uint8_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::uint8_t | قيمة عدد صحيح غير موقع 8-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::uint16_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::uint16_t | قيمة عدد صحيح غير موقع 16-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::uint32_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::uint32_t | قيمة عدد صحيح غير موقع 32-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(std::uint64_t) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | std::uint64_t | قيمة عدد صحيح غير موقع 64-بت لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(float) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(float f)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| f | **float** | قيمة نقطية ذات دقة أحادية لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(double) منشئ

ينشئ كائنًا يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(double d)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | **double** | قيمة نقطية ذات دقة مزدوجة لتمثيله بواسطة الكائن [Decimal](../) الذي يتم بناؤه |

## Decimal::Decimal(const std::string\&) منشئ

ينشئ كائنًا يمثل قيمة تم تمثيلها كسلسلة محددة ككائن من فئة std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) منشئ

ينشئ كائن [Decimal](../) من المكونات المحددة.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lo | **int32_t** | الـ 32 بت الأقل قيمة |
| mid | **int32_t** | الـ 32 بت المتوسطة قيمة |
| hi | **int32_t** | الـ 32 بت الأعلى قيمة |
| isNegative | **bool** | يحدد ما إذا كانت القيمة سلبية |
| scale | **uint8_t** | قوة 10 تتراوح بين 0 و 28 |

## Decimal::Decimal(const Decimal\&) منشئ

ينشئ كائن من فئة [Decimal](../) يمثل نفس الرقم مثل الكائن [Decimal](../) المحدد.

```cpp
System::Decimal::Decimal(const Decimal &d)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../)\& | كائن [Decimal](../) لنسخ القيمة منه |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) منشئ

ينشئ كائن من فئة [Decimal](../) من مصفوفة عددية تحتوي على تمثيل ثنائي.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | مصفوفة عددية تحتوي على تمثيل ثنائي. |

## Decimal::Decimal(std::nullptr_t) منشئ

دائمًا ما يلقي استثناء ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) منشئ

ينشئ كائن من فئة [Decimal](../) يمثل القيمة المحددة.

```cpp
System::Decimal::Decimal(const number_type &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | إشارة ثابتة إلى القيمة التي ستمثلها الكائن الذي يتم بناؤه |

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* فئة [Decimal](../)
* نطاق [System](../../)
* Library [Aspose.Slides](../../../)