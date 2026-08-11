---
title: DateTimeOffset()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منشئ افتراضي.
type: docs
weight: 1
url: /ar/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() منشئ


منشئ افتراضي.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | التاريخ والوقت. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ticks | **int64_t** | عدد النقرات. |
| offset | [TimeSpan](../../timespan/) | إزاحة الوقت عن التوقيت العالمي. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | التاريخ والوقت. |
| offset | [TimeSpan](../../timespan/) | إزاحة الوقت عن التوقيت العالمي. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة (من 1 إلى 9999). |
| month | int | الشهر (من 1 إلى 12). |
| day | int | اليوم (من 1 إلى عدد الأيام في الشهر). |
| hour | int | الساعة (من 0 إلى 23). |
| minute | int | الدقيقة (من 0 إلى 59). |
| second | int | الثانية (من 0 إلى 59). |
| offset | [TimeSpan](../../timespan/) | إزاحة الوقت عن التوقيت العالمي. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة (من 1 إلى 9999). |
| month | int | الشهر (من 1 إلى 12). |
| day | int | اليوم (من 1 إلى عدد الأيام في الشهر). |
| hour | int | الساعة (من 0 إلى 23). |
| minute | int | الدقيقة (من 0 إلى 59). |
| second | int | الثانية (من 0 إلى 59). |
| millisecond | int | المللي ثانية (من 0 إلى 999). |
| offset | [TimeSpan](../../timespan/) | إزاحة الوقت عن التوقيت العالمي. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) منشئ


منشئ.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| year | int | السنة. |
| month | int | الشهر (من 1 إلى 12). |
| day | int | اليوم (من 1 إلى عدد الأيام في الشهر). |
| hour | int | الساعة (من 0 إلى 23). |
| minute | int | الدقيقة (من 0 إلى 59). |
| second | int | الثانية (من 0 إلى 59). |
| millisecond | int | المللي ثانية (من 0 إلى 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | التقويم المستخدم لتفسير السنة والشهر واليوم. |
| offset | [TimeSpan](../../timespan/) | إزاحة الوقت عن التوقيت العالمي. |

## انظر أيضا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [DateTimeOffset](../)
* فئة [DateTime](../../datetime/)
* فئة [TimeSpan](../../timespan/)
* فئة [Calendar](../../../system.globalization/calendar/)
* فضاء الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)