---
title: Math
second_title: Aspose.Slides for C++ API Reference
description: Contains math functions. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 1678
url: /system/math/
---
## Math struct


Contains math functions. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Math
```

## Methods

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | Returns the absolute value of the specified value. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Returns the absolute value of a value represented by the specified [Decimal](../decimal/) object. |
| static **double** [Acos](./acos/)(**double**) | Calculates the arccosine of the specified value. |
| static **double** [Asin](./asin/)(**double**) | Calculates the arcsin of the specified value. |
| static **double** [Atan](./atan/)(**double**) | Calculates the arctan of the specified value. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Calculates the arctan of the ration of the specified values. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Returns the full product of two 32-bit integers. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Returns the smallest integral value that is greater than or equal to the specified value. |
| static **double** [Ceiling](./ceiling/)(**double**) | Returns the smallest integral value that is greater than or equal to the specified value. |
| static **double** [Cos](./cos/)(**double**) | Calculates the cosine of the specified value. |
| static **double** [Cosh](./cosh/)(**double**) | Calculates the hyperbolic cosine of the specified value. |
| static int [DivRem](./divrem/)(int, int, int\&) | Calculates the quotient of two 32-bit integers and the remainder. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Calculates the quotient of two 64-bit integers and the remainder. |
| static **double** [Exp](./exp/)(**double**) | Returns e constant raised to the specified power. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Returns the largest integral value that is less than or equal to the specified value. |
| static **double** [Floor](./floor/)(**double**) | Returns the largest integral value that is less than or equal to the specified value. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Returns the remainder resulting from the division of a specified number by another specified number. |
| static **double** [Log](./log/)(**double**) | Returns the natural logarithm of the specified value. |
| static **double** [Log](./log/)(**double**, **double**) | Returns the logarithm of the specified value in the specified base. |
| static **double** [Log10](./log10/)(**double**) | Returns the base-10 logarithm of the specified value. |
| static auto [Max](./max/)(T0, T1) | Returns the greatest value out of two numeric ones specified. |
| static T0 [Max](./max/)(T0, T1) | Returns the greatest value out of two numeric ones specified. |
| **float** [Max_](./max_/)(**float**, **float**) | Returns the largest single-precision floating point value out of the two specified. |
| **double** [Max_](./max_/)(**double**, **double**) | Returns the largest double-precision floating point value out of the two specified. |
| static auto [Min](./min/)(T0, T1) | Returns the smallest value out of two numeric ones specified. |
| static T0 [Min](./min/)(T0, T1) | Returns the smallest value out of two numeric ones specified. |
| **float** [Min_](./min_/)(**float**, **float**) | Returns the smallest single-precision floating point value out of the two specified. |
| **double** [Min_](./min_/)(**double**, **double**) | Returns the smallest double-precision floating point value out of the two specified. |
| static T [Modulus](./modulus/)(T, T) | Calculates the remainder resulting from the division one specified value by another specified value. |
| static **double** [Pow](./pow/)(**double**, **double**) | Returns the specified value raised to the specified power. |
| static **double** [Round](./round/)(**double**) | Rounds the specified value to the nearest integral value. |
| static **double** [Round](./round/)(**double**, int) | Rounds the specified value to the nearest value with the specified number of fractional digits. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Rounds the specified value to the nearest integral value. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Rounds the specified value to the nearest value with the specified number of fractional digits. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determines the sign of the specified signed integral value. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determines the sign of the specified floating-point value. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Determines the sign of the specified decimal value. |
| static **double** [Sin](./sin/)(**double**) | Calculates the sine of the specified value. |
| static **double** [Sinh](./sinh/)(**double**) | Calculates the hyperbolic sine of the specified value. |
| static **double** [Sqrt](./sqrt/)(**double**) | Returns the square root of the specified value. |
| static **double** [Tan](./tan/)(**double**) | Calculates the tangen of the specified value. |
| static **double** [Tanh](./tanh/)(**double**) | Calculates the hyperbolic tangen of the specified value. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Returns the [Decimal](../decimal/) object representing a value that has integral part equal to that of the value represented by the specified [Decimal](../decimal/) object of the with all fractional digits discarded. |
| static **double** [Truncate](./truncate/)(**double**) | Returns a double-precision floating point value that has integral part equal to that of the specified value with all fractional digits discarded. |
## Fields

| Field | Description |
| --- | --- |
| static [E](./e/) | Natural logarithm's base. |
| static [NaN](./nan/) | Represents a not-a-number value. |
| static [NegativeInfinity](./negativeinfinity/) | Represents the negative infinity. |
| static [PI](./pi/) | The number Pi constant. |
| static [PositiveInfinity](./positiveinfinity/) | Represents the positive infinity. |
## Remarks



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Print the absolute values.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Print the sine of PI/2 and the cosine of PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
This code example produces the following output:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)