---
title: DateTime()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance that represents the smallest possible date and time value equal to MinValue.
type: docs
weight: 1
url: /cpp/system/datetime/datetime/
---
## DateTime::DateTime() constructor


Constructs an instance that represents the smallest possible date and time value equal to MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int) constructor


Constructs an instance that represents a date and time value specified as a particular year, month and day.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\&) constructor


Constructs an instance that represents a date and time value specified as a particular year, month and day in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, int, int, int) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |

## See Also

* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, int, int, int, [DateTimeKind](../../datetimekind/)) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| kind | [DateTimeKind](../../datetimekind/) | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, int, int, int, const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\&) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute and second in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, [DateTimeKind](../../datetimekind/)) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| millisecond | int | The millisecond of the **second** to be represented by the instance being constructed. |
| kind | [DateTimeKind](../../datetimekind/) | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(int, int, int, int, int, int, int, const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\&, [DateTimeKind](../../datetimekind/)) constructor


Constructs an instance that represents a date and time value specified as a particular year, month, day, hour, minute, second and millisecond in the specified calendar.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| year | int | The year to be represented by the instance being constructed. |
| month | int | The month of the **year** to be represented by the instance being constructed. |
| day | int | The day of the **month** to be represented by the instance being constructed. |
| hour | int | The hour of the **day** to be represented by the instance being constructed. |
| minute | int | The minute of the **hour** to be represented by the instance being constructed. |
| second | int | The second of the **minute** te be represented by the instance being constructed. |
| millisecond | int | The millisecond of the **second** to be represented by the instance being constructed. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | The value that indicates if the provided date and time parameters specify a local time, UTC time or neither. |
| calendar | [DateTimeKind](../../datetimekind/) | The calendar used to interpret the specified **year**, **month** and **day**. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Calendar](../../../system.globalization/calendar/)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(**int64_t**, [DateTimeKind](../../datetimekind/)) constructor


Construct an instance that represents a date and time value specified as a number of ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | The number of 100-ns intervals that have passed since January the 1st, 0001 00:00:00.000 in Georgian calendar. |
| kind | [DateTimeKind](../../datetimekind/) | The value that indicates if **ticks** parameter specifies a local time, UTC time or neither. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(**int64_t**, [DateTimeKind](../../datetimekind/), **bool**) constructor


Construct an instance that represents a date and time value specified as a number of ticks. FOR INTERNAL USE.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | The number of 100-ns intervals that have passed since January the 1st, 0001 00:00:00.000 in Georgian calendar. |
| kind | [DateTimeKind](../../datetimekind/) | The value that indicates if **ticks** parameter specifies a local time, UTC time or neither. |
| is_ambiguous_local_dst | **bool** | True if specified date and time is ambiguous and can be mapped to many UTC times. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DateTime::DateTime(const [DateTime](../)\&) constructor


Copy-constructs an instance.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dt | const [DateTime](../)\& | An instance of [DateTime](../) class to copy the represented date and time value from |

## See Also

* Class [DateTime](../)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
