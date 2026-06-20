---
title: Round()
second_title: Aspose.Slides for C++ API Reference
description: Rounds the specified value to the nearest integral value.
type: docs
weight: 157
url: /system/mathf/round/
---
## MathF::Round(float) method


Rounds the specified value to the nearest integral value.

```cpp
static float System::MathF::Round(float a)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | **float** | The value to round |

### Return Value

**a** rounded to the nearest integral value

## MathF::Round(float, int) method


Rounds the specified value to the nearest value with the specified number of fractional digits.

```cpp
static float System::MathF::Round(float value, int digits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to round |
| digits | int | The number of fractional digits in the rounded value |

### Return Value

The number with the specified number of digits nearest to **value**

## MathF::Round(float, MidpointRounding) method


Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**value** rounded to the nearest integral value

## MathF::Round(float, int, MidpointRounding) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

The number with the specified number of digits nearest to **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)