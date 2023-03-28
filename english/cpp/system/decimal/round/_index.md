---
title: Round()
second_title: Aspose.Slides for C++ API Reference
description: Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.
type: docs
weight: 404
url: /cpp/system/decimal/round/
---
## Decimal::Round(const [Decimal](../)\&, [MidpointRounding](../../midpointrounding/)) method


Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**d** rounded to the nearest integral value

## See Also

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Decimal::Round(const [Decimal](../)\&, int, [MidpointRounding](../../midpointrounding/)) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

The number with the specified number of digits nearest to **value**

## See Also

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
