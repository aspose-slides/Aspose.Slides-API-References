---
title: Subtract()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يعيد نسخة جديدة من الفئة DateTime تمثل قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي.
type: docs
weight: 326
url: /ar/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const طريقة

يعيد نسخة جديدة من الفئة [DateTime](../) تمثل قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | فاصل زمني للطرح |

### قيمة الإرجاع

نسخة جديدة من الفئة [DateTime](../) تمثل قيمة التاريخ والوقت التي هي نتيجة طرح **duration** من القيمة التي يمثلها الكائن الحالي.

## DateTime::Subtract(DateTime) const طريقة

يعيد نسخة من الفئة [TimeSpan](../../timespan/) تمثل الفاصل الزمني بين قيمتي التاريخ والوقت التي يمثلها الكائن الحالي والكائن المحدد.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../) | نسخة من الفئة [DateTime](../) تحدد أحد طرفي الفاصل الزمني المراد حسابه |

### قيمة الإرجاع

نسخة من الفئة [TimeSpan](../../timespan/) تمثل الفاصل الزمني بين قيمتي التاريخ والوقت التي يمثلها الكائن الحالي و **value**.

## شاهد أيضًا

* الفئة [DateTime](../)
* الفئة [TimeSpan](../../timespan/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)