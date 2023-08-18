---
title: Round()
second_title: Aspose.Slides for C++ API Reference
description: Rounds the specified value to the nearest integral value.
type: docs
weight: 157
url: /system/math/round/
---
## Math::Round(double) method


Rounds the specified value to the nearest integral value.

```cpp
static double System::Math::Round(double a)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | **double** | The value to round |

### Return Value

**a** rounded to the nearest integral value

## Math::Round(double, int) method


Rounds the specified value to the nearest value with the specified number of fractional digits.

```cpp
static double System::Math::Round(double value, int digits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| digits | int | The number of fractional digits in the rounded value |

### Return Value

The number with the specified number of digits nearest to **value**

## Math::Round(double, MidpointRounding) method


Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**value** rounded to the nearest integral value

## Math::Round(double, int, MidpointRounding) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

The number with the specified number of digits nearest to **value**

## Math::Round(const Decimal\&) method


Rounds the specified value to the nearest integral value.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |

### Return Value

**d** rounded to the nearest integral value

## Math::Round(const Decimal\&, int) method


Rounds the specified value to the nearest value with the specified number of fractional digits.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |

### Return Value

The number with the specified number of digits nearest to **value**

## Math::Round(const Decimal\&, MidpointRounding) method


Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

**d** rounded to the nearest integral value

## Math::Round(const Decimal\&, int, MidpointRounding) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

The number with the specified number of digits nearest to **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)