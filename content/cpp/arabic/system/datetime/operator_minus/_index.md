---
title: operator-()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إرجاع نسخة جديدة من الفئة DateTime التي تمثل قيمة التاريخ والوقت التي هي نتيجة طرح فترة الوقت المحددة من القيمة التي يمثلها الكائن الحالي.
type: docs
weight: 651
url: /ar/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const طريقة

إرجاع نسخة جديدة من الفئة [DateTime](../) التي تمثل قيمة التاريخ والوقت التي هي نتيجة طرح فترة الوقت المحددة من القيمة التي يمثلها الكائن الحالي.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | فترة زمنية للطرح |

### قيمة الإرجاع

نسخة جديدة من الفئة [DateTime](../) التي تمثل قيمة التاريخ والوقت التي هي نتيجة طرح **value** من القيمة التي يمثلها الكائن الحالي.

## DateTime::operator-(DateTime) const طريقة

إرجاع نسخة من الفئة [TimeSpan](../../timespan/) التي تمثل الفاصل الزمني بين قيم التاريخ والوقت التي يمثلها الكائن الحالي والكائن المحدد.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | [DateTime](../) | نسخة من الفئة [DateTime](../) التي تشير إلى أحد طرفي الفاصل الزمني الذي سيُحسب |

### قيمة الإرجاع

نسخة من الفئة [TimeSpan](../../timespan/) التي تمثل الفاصل الزمني بين قيم التاريخ والوقت التي يمثلها الكائن الحالي و **value**.

## انظر أيضًا

* الفئة [DateTime](../)
* الفئة [TimeSpan](../../timespan/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)