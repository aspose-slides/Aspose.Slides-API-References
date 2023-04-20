---
title: TimeSpan()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a TimeSpan object that represents a zero time interval.
type: docs
weight: 1
url: /cpp/system/timespan/timespan/
---
## TimeSpan::TimeSpan() constructor


Constructs a [TimeSpan](../) object that represents a zero time interval.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) constructor


Constructs an instance of [TimeSpan](../) class that represents the specified time interval.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | The time interval to be represented by the instance being constructed expressed as the number of 100-nanoseconds intervals. |

## TimeSpan::TimeSpan(int, int, int) constructor


Constructs an instance of [TimeSpan](../) class that represents the time interval which is equal to the sum of the specified number of hours, minutes and seconds.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hours | int | The number of hours in the hours component of the time interval to be represented by the instance being constructed |
| minutes | int | The number of minutes in the minutes component of the time interval to be represented by the instance being constructed |
| seconds | int | The number of seconds in the seconds component of the time interval to be represented by the instance being constructed |

## TimeSpan::TimeSpan(int, int, int, int, int) constructor


Constructs an instance of [TimeSpan](../) class that represents the time interval which is equal to the sum of the specified number of hours, minutes, seconds and milliseconds.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| days | int | The number of days in the days component of the time interval to be represented by the instance being constructed |
| hours | int | The number of hours in the hours component of the time interval to be represented by the instance being constructed |
| minutes | int | The number of minutes in the minutes component of the time interval to be represented by the instance being constructed |
| seconds | int | The number of seconds in the seconds component of the time interval to be represented by the instance being constructed |
| milliseconds | int | The number of milliseconds in the milliseconds component of the time interval to be represented by the instance being constructed |

## TimeSpan::TimeSpan(const TimeSpan\&) constructor


Constructs a [TimeSpan](../) object that represents the time interval equal to the time interval represented by the specified [TimeSpan](../) object.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## See Also

* Class [TimeSpan](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)