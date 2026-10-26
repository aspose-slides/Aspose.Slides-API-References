---
title: DateTime()
second_title: مرجع API لـ Aspose.Slides for C++
description: ينشئ كائنًا يمثل أصغر قيمة ممكنة للتاريخ والوقت مساوية لـ MinValue.
type: docs
weight: 1
url: /ar/system/datetime/datetime/
---
## DateTime::DateTime() منشئ

يقوم بإنشاء كائن يمثل أصغر قيمة ممكنة للتاريخ والوقت مساوية لـ MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم معينين.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم معينين في التقويم المحدد.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | التقويم المستخدم لتفسير **السنة** و**الشهر** و**اليوم** المحددين. |

## DateTime::DateTime(int, int, int, int, int, int) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم وساعة ودقيقة وثانية معينة.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| hour | int | ساعة **اليوم** التي سيُمثَّلها الكائن المُنشأ. |
| minute | int | دقيقة **الساعة** التي سيُمثَّلها الكائن المُنشأ. |
| second | int | ثانية **الدقيقة** التي سيُمثَّلها الكائن المُنشأ. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم وساعة ودقيقة وثانية معينة.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| hour | int | ساعة **اليوم** التي سيُمثَّلها الكائن المُنشأ. |
| minute | int | دقيقة **الساعة** التي سيُمثَّلها الكائن المُنشأ. |
| second | int | ثانية **الدقيقة** التي سيُمثَّلها الكائن المُنشأ. |
| kind | [DateTimeKind](../../datetimekind/) | القيمة التي تحدد ما إذا كانت معلمات التاريخ والوقت المحددة تمثل وقتاً محلياً أو توقيت UTC أو لا شيء منهما. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم وساعة ودقيقة وثانية في التقويم المحدد.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| hour | int | ساعة **اليوم** التي سيُمثَّلها الكائن المُنشأ. |
| minute | int | دقيقة **الساعة** التي سيُمثَّلها الكائن المُنشأ. |
| second | int | ثانية **الدقيقة** التي سيُمثَّلها الكائن المُنشأ. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | التقويم المستخدم لتفسير **السنة** و**الشهر** و**اليوم** المحددين. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم وساعة ودقيقة وثانية وملي ثانية معينة.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| hour | int | ساعة **اليوم** التي سيُمثَّلها الكائن المُنشأ. |
| minute | int | دقيقة **الساعة** التي سيُمثَّلها الكائن المُنشأ. |
| second | int | ثانية **الدقيقة** التي سيُمثَّلها الكائن المُنشأ. |
| millisecond | int | مللي ثانية **الثانية** التي سيُمثَّلها الكائن المُنشأ. |
| kind | [DateTimeKind](../../datetimekind/) | القيمة التي تحدد ما إذا كانت معلمات التاريخ والوقت المحددة تمثل وقتاً محلياً أو توقيت UTC أو لا شيء منهما. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة بسنة وشهر ويوم وساعة ودقيقة وثانية وملي ثانية في التقويم المحدد.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة التي سيُمثَّلها الكائن المُنشأ. |
| month | int | شهر **السنة** الذي سيُمثَّل بالكائن المُنشأ. |
| day | int | يوم **الشهر** الذي سيُمثَّل بالكائن المُنشأ. |
| hour | int | ساعة **اليوم** التي سيُمثَّلها الكائن المُنشأ. |
| minute | int | دقيقة **الساعة** التي سيُمثَّلها الكائن المُنشأ. |
| second | int | ثانية **الدقيقة** التي سيُمثَّلها الكائن المُنشأ. |
| millisecond | int | مللي ثانية **الثانية** التي سيُمثَّلها الكائن المُنشأ. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | القيمة التي تحدد ما إذا كانت معلمات التاريخ والوقت المحددة تمثل وقتاً محلياً أو توقيت UTC أو لا شيء منهما. |
| calendar | [DateTimeKind](../../datetimekind/) | التقويم المستخدم لتفسير **السنة** و**الشهر** و**اليوم** المحددين. |

## DateTime::DateTime(int64_t, DateTimeKind) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة كعدد من الوحدات النقية.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ticks | **int64_t** | عدد فواصل 100 نانوثانية التي مرت منذ 1 يناير 0001 00:00:00.000 في التقويم الجريجوري. |
| kind | [DateTimeKind](../../datetimekind/) | القيمة التي تحدد ما إذا كانت معلمة **ticks** تمثل وقتاً محلياً أو توقيت UTC أو لا شيء منهما. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) منشئ

يقوم بإنشاء كائن يمثل قيمة تاريخ ووقت محددة كعدد من الوحدات النقية. للاستخدام الداخلي فقط.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ticks | **int64_t** | عدد فواصل 100 نانوثانية التي مرت منذ 1 يناير 0001 00:00:00.000 في التقويم الجريجوري. |
| kind | [DateTimeKind](../../datetimekind/) | القيمة التي تحدد ما إذا كانت معلمة **ticks** تمثل وقتاً محلياً أو توقيت UTC أو لا شيء منهما. |
| is_ambiguous_local_dst | **bool** | true إذا كان التاريخ والوقت المحددان غامضين ويمكن ربطهما بالعديد من أوقات UTC. |

## DateTime::DateTime(const DateTime\&) منشئ

ينشئ نسخةً من كائن موجود.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dt | const [DateTime](../)\& | نسخة من فئة [DateTime](../) يتم نسخ قيمة التاريخ والوقت الممثلة منها. |

## انظر أيضًا

* تعداد [DateTimeKind](../../datetimekind/)
* تعريف_نوع [SharedPtr](../../sharedptr/)
* فئة [DateTime](../)
* فئة [Calendar](../../../system.globalization/calendar/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)