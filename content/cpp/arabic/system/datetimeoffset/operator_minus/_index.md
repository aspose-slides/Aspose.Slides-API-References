---
title: operator-()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرجع نسخة جديدة من فئة DateTimeOffset تمثل قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي.
type: docs
weight: 521
url: /ar/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const طريقة

يعيد نسخة جديدة من الفئة [DateTimeOffset](../) تمثل قيمة التاريخ والوقت التي هي نتيجة طرح الفاصل الزمني المحدد من القيمة التي يمثلها الكائن الحالي.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | فاصل زمني يتم طرحه |

### قيمة الإرجاع

نسخة جديدة من الفئة [DateTimeOffset](../) تمثل قيمة التاريخ والوقت التي هي نتيجة طرح **value** من القيمة التي يمثلها الكائن الحالي.

## DateTimeOffset::operator-(const DateTimeOffset\&) const طريقة

يعيد نسخة من الفئة [TimeSpan](../../timespan/) تمثل الفاصل الزمني بين قيم التاريخ والوقت التي يمثلها الكائن الحالي والكائن المحدد.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | نسخة من الفئة [DateTime](../../datetime/) تمثل أحد طرفي الفاصل الزمني المراد حسابه |

### قيمة الإرجاع

نسخة من الفئة [TimeSpan](../../timespan/) تمثل الفاصل الزمني بين قيم التاريخ والوقت التي يمثلها الكائن الحالي و **other**.

## انظر أيضًا

* الفئة [DateTimeOffset](../)
* الفئة [TimeSpan](../../timespan/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)