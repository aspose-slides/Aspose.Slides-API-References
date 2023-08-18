---
title: Subtract()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new instance of the DateTime class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.
type: docs
weight: 326
url: /system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const method


Returns a new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | A time interval to subtract |

### Return Value

A new instance of the [DateTime](../) class representing the date and time value which is the result of subtraction of **duration** from the value represented by the current object.

## DateTime::Subtract(DateTime) const method


Returns an instance of [TimeSpan](../../timespan/) class representing the time interval between the date and time values represented by the current and the specified objects.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | An instance of [DateTime](../) class that marks one end of the interval to be calculated |

### Return Value

An instance of [TimeSpan](../../timespan/) class representing the time interval between the date and time values represented by the current object and **value**.

## See Also

* Class [DateTime](../)
* Class [TimeSpan](../../timespan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)