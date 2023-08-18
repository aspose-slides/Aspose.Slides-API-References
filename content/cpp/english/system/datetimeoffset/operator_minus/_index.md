---
title: operator-()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new instance of the DateTimeOffset class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.
type: docs
weight: 521
url: /system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const method


Returns a new instance of the [DateTimeOffset](../) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | A time interval to subtract |

### Return Value

A new instance of the [DateTimeOffset](../) class representing the date and time value which is the result of subtraction of **value** from the value represented by the current object.

## DateTimeOffset::operator-(const DateTimeOffset\&) const method


Returns an instance of [TimeSpan](../../timespan/) class that represents the time interval between the date and time values represented by the current and the specified objects.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | An instance of [DateTime](../../datetime/) class that marks one end of the interval to be calculated |

### Return Value

An instance of [TimeSpan](../../timespan/) class representing the time interval between the date and time values represented by the current object and **other**.

## See Also

* Class [DateTimeOffset](../)
* Class [TimeSpan](../../timespan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)