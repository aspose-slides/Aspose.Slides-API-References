---
title: DateTimeOffset()
second_title: Aspose.Slides for C++ API Reference
description: Default constructor.
type: docs
weight: 1
url: /cpp/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor


Default constructor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## See Also

* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset([DateTime](../../datetime/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time. |

## See Also

* Class [DateTime](../../datetime/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset(**int64_t**, [TimeSpan](../../timespan/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | Number of ticks. |
| offset | [TimeSpan](../../timespan/) | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset([DateTime](../../datetime/), [TimeSpan](../../timespan/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time. |
| offset | [TimeSpan](../../timespan/) | Time offset from UTC. |

## See Also

* Class [DateTime](../../datetime/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, [TimeSpan](../../timespan/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year (1 through 9999). |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| offset | [TimeSpan](../../timespan/) | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, [TimeSpan](../../timespan/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year (1 through 9999). |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| millisecond | int | Millisecond (0 through 999). |
| offset | [TimeSpan](../../timespan/) | Time offset from UTC. |

## See Also

* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\&, [TimeSpan](../../timespan/)) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | Year. |
| month | int | Month (1 through 12). |
| day | int | Day (1 through the number of days in month). |
| hour | int | Hour (0 through 23). |
| minute | int | Minute (0 through 59). |
| second | int | Second (0 through 59). |
| millisecond | int | Millisecond (0 through 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Calendar used to interpret year, month, and day. |
| offset | [TimeSpan](../../timespan/) | Time offset from UTC. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [TimeSpan](../../timespan/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
