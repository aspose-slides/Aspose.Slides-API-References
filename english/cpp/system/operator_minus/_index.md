---
title: operator-()
second_title: Aspose.Slides for C++ API Reference
description: Calculates the number of days between two days of week.
type: docs
weight: 2003
url: /cpp/system/operator_minus/
---
## System::operator-([DayOfWeek](../dayofweek/), [DayOfWeek](../dayofweek/)) function


Calculates the number of days between two days of week.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### Return Value

The number of days between weekdays **a** and **b**; the return value is a negative number if *goes* after ****

## See Also

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator-(const T\&, const [Decimal](../decimal/)\&) function


Returns a new instance of [Decimal](../decimal/) class that represents a value that is the result of subtraction of the value represented by the specified [Decimal](../decimal/) object from the specified value.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | The value to subtract from |
| d | const [Decimal](../decimal/)\& | The [Decimal](../decimal/) object representing the subtracted value |

### Return Value

A new instance of [Decimal](../decimal/) class that represents a value that is the result of subtraction of the value represented by **d** from **x**.

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator-(const T1\&, const [Nullable](../nullable/)\<T2\>\&) function


Subtracts non-nullable and nullable values.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### Return Value

Substation result.

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
