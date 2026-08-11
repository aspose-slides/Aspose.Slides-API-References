---
title: DateTimeOffset()
second_title: مستندات API Aspose.Slides برای C++
description: سازنده پیش‌فرض.
type: docs
weight: 1
url: /fa/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() سازنده

سازنده پیش‌فرض.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | تاریخ و زمان. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | تعداد تیک‌ها. |
| offset | [TimeSpan](../../timespan/) | اختلاف زمان از UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | تاریخ و زمان. |
| offset | [TimeSpan](../../timespan/) | اختلاف زمان از UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | سال (از 1 تا 9999). |
| month | int | ماه (از 1 تا 12). |
| day | int | روز (از 1 تا تعداد روزهای ماه). |
| hour | int | ساعت (از 0 تا 23). |
| minute | int | دقیقه (از 0 تا 59). |
| second | int | ثانیه (از 0 تا 59). |
| offset | [TimeSpan](../../timespan/) | اختلاف زمان از UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | سال (از 1 تا 9999). |
| month | int | ماه (از 1 تا 12). |
| day | int | روز (از 1 تا تعداد روزهای ماه). |
| hour | int | ساعت (از 0 تا 23). |
| minute | int | دقیقه (از 0 تا 59). |
| second | int | ثانیه (از 0 تا 59). |
| millisecond | int | میلی‌ثانیه (از 0 تا 999). |
| offset | [TimeSpan](../../timespan/) | اختلاف زمان از UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) سازنده

سازنده.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | سال. |
| month | int | ماه (از 1 تا 12). |
| day | int | روز (از 1 تا تعداد روزهای ماه). |
| hour | int | ساعت (از 0 تا 23). |
| minute | int | دقیقه (از 0 تا 59). |
| second | int | ثانیه (از 0 تا 59). |
| millisecond | int | میلی‌ثانیه (از 0 تا 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | تقویمی که برای تفسیر سال، ماه و روز استفاده می‌شود. |
| offset | [TimeSpan](../../timespan/) | اختلاف زمان از UTC. |

## موارد مرتبط

* Typedef [SharedPtr](../../sharedptr/)
* کلاس [DateTimeOffset](../)
* کلاس [DateTime](../../datetime/)
* کلاس [TimeSpan](../../timespan/)
* کلاس [Calendar](../../../system.globalization/calendar/)
* فضای‌نام [System](../../)
* Library [Aspose.Slides](../../../)