---
title: MathF
second_title: Aspose.Slides for C++ API Reference
description: Contains math functions for single-precision floating-point values. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 1769
url: /system/mathf/
---
## MathF struct


Contains math functions for single-precision floating-point values. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class MathF
```

## Methods

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Returns the absolute value of the specified value. |
| static **float** [Acos](./acos/)(**float**) | Calculates the arccosine of the specified value. |
| static **float** [Asin](./asin/)(**float**) | Calculates the arcsin of the specified value. |
| static **float** [Atan](./atan/)(**float**) | Calculates the arctan of the specified value. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Calculates the arctan of the ration of the specified values. |
| static **float** [Ceiling](./ceiling/)(**float**) | Returns the smallest integral value that is greater than or equal to the specified value. |
| static **float** [Cos](./cos/)(**float**) | Calculates the cosine of the specified value. |
| static **float** [Cosh](./cosh/)(**float**) | Calculates the hyperbolic cosine of the specified value. |
| static **float** [Exp](./exp/)(**float**) | Returns e constant raised to the specified power. |
| static **float** [Floor](./floor/)(**float**) | Returns the largest integral value that is less than or equal to the specified value. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Returns the remainder resulting from the division of a specified number by another specified number. |
| static **float** [Log](./log/)(**float**) | Returns the natural logarithm of the specified value. |
| static **float** [Log](./log/)(**float**, **float**) | Returns the logarithm of the specified value in the specified base. |
| static **float** [Log10](./log10/)(**float**) | Returns the base-10 logarithm of the specified value. |
| static **float** [Pow](./pow/)(**float**, **float**) | Returns the specified value raised to the specified power. |
| static **float** [Round](./round/)(**float**) | Rounds the specified value to the nearest integral value. |
| static **float** [Round](./round/)(**float**, int) | Rounds the specified value to the nearest value with the specified number of fractional digits. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determines the sign of the specified signed integral value. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determines the sign of the specified floating-point value. |
| static **float** [Sin](./sin/)(**float**) | Calculates the sine of the specified value. |
| static **float** [Sinh](./sinh/)(**float**) | Calculates the hyperbolic sine of the specified value. |
| static **float** [Sqrt](./sqrt/)(**float**) | Returns the square root of the specified value. |
| static **float** [Tan](./tan/)(**float**) | Calculates the tangen of the specified value. |
| static **float** [Tanh](./tanh/)(**float**) | Calculates the hyperbolic tangen of the specified value. |
| static **float** [Truncate](./truncate/)(**float**) | Returns a float-precision floating point value that has integral part equal to that of the specified value with all fractional digits discarded. |
## Fields

| Field | Description |
| --- | --- |
| static [E](./e/) | Natural logarithm's base. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | The number Pi constant. |
| static [Tau](./tau/) | Tau value. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)