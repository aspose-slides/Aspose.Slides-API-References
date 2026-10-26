---
title: TimeSpan()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن TimeSpan يمثل فاصلًا زمنيًا يساوي الصفر.
type: docs
weight: 1
url: /ar/system/timespan/timespan/
---
## TimeSpan::TimeSpan() مُنشئ

ينشئ كائن [TimeSpan](../) يمثل فاصلًا زمنيًا يساوي الصفر.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) مُنشئ

ينشئ نسخة من الفئة [TimeSpan](../) تمثل الفاصل الزمني المحدد.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها، معبرًا عنه بعدد فواصل 100 نانوثانية. |

## TimeSpan::TimeSpan(int, int, int) مُنشئ

ينشئ نسخة من الفئة [TimeSpan](../) تمثل الفاصل الزمني الذي يساوي مجموع عدد الساعات والدقائق والثواني المحددة.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| hours | int | عدد الساعات في عنصر hours من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| minutes | int | عدد الدقائق في عنصر minutes من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| seconds | int | عدد الثواني في عنصر seconds من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |

## TimeSpan::TimeSpan(int, int, int, int, int) مُنشئ

ينشئ نسخة من الفئة [TimeSpan](../) تمثل الفاصل الزمني الذي يساوي مجموع عدد الساعات والدقائق والثواني والمللي ثانية المحددة.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| days | int | عدد الأيام في عنصر days من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| hours | int | عدد الساعات في عنصر hours من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| minutes | int | عدد الدقائق في عنصر minutes من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| seconds | int | عدد الثواني في عنصر seconds من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |
| milliseconds | int | عدد المللي ثانية في عنصر milliseconds من الفاصل الزمني الذي سيُمثَّل بالنسخة التي يجري إنشاؤها |

## TimeSpan::TimeSpan(const TimeSpan\&) مُنشئ

ينشئ كائن [TimeSpan](../) يمثل الفاصل الزمني الذي يساوي الفاصل الزمني الممثل بواسطة الكائن [TimeSpan](../) المحدد.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## انظر أيضًا

* الفئة [TimeSpan](../)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)