---
title: Math
second_title: Aspose.Slides for C++ API 参考
description: 包含数学函数。这是一个没有实例服务的静态类型。任何情况下都不应创建其实例。
type: docs
weight: 1756
url: /zh/system/math/
---
## Math struct

包含数学函数。这是一个没有实例服务的静态类型。任何情况下都不应创建其实例。

```cpp
class Math
```

## 方法

| Method | Description |
| --- | --- |
| static T [Abs](./abs/)(T) | 返回指定值的绝对值。 |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | 返回由指定的 [Decimal](../decimal/) 对象表示的值的绝对值。 |
| static **double** [Acos](./acos/)(**double**) | 计算指定值的反余弦。 |
| static **double** [Asin](./asin/)(**double**) | 计算指定值的反正弦。 |
| static **double** [Atan](./atan/)(**double**) | 计算指定值的反正切。 |
| static **double** [Atan2](./atan2/)(**double**, **double**) | 计算指定值比例的反正切。 |
| static **int64_t** [BigMul](./bigmul/)(int, int) | 返回两个 32 位整数的完整乘积。 |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | 返回大于或等于指定值的最小整数值。 |
| static **double** [Ceiling](./ceiling/)(**double**) | 返回大于或等于指定值的最小整数值。 |
| static **double** [Cos](./cos/)(**double**) | 计算指定值的余弦。 |
| static **double** [Cosh](./cosh/)(**double**) | 计算指定值的双曲余弦。 |
| static int [DivRem](./divrem/)(int, int, int\&) | 计算两个 32 位整数的商和余数。 |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | 计算两个 64 位整数的商和余数。 |
| static **double** [Exp](./exp/)(**double**) | 返回 e 常数的指定次幂。 |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | 返回小于或等于指定值的最大整数值。 |
| static **double** [Floor](./floor/)(**double**) | 返回小于或等于指定值的最大整数值。 |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | 返回指定数除以另一个指定数的余数。 |
| static **double** [Log](./log/)(**double**) | 返回指定值的自然对数。 |
| static **double** [Log](./log/)(**double**, **double**) | 返回指定基数下指定值的对数。 |
| static **double** [Log10](./log10/)(**double**) | 返回指定值的以 10 为底的对数。 |
| static auto [Max](./max/)(T0, T1) | 返回两个指定数值中的最大值。 |
| static T0 [Max](./max/)(T0, T1) | 返回两个指定数值中的最大值。 |
| **float** [Max_](./max_/)(**float**, **float**) | 返回两个指定的单精度浮点数中的最大值。 |
| **double** [Max_](./max_/)(**double**, **double**) | 返回两个指定的双精度浮点数中的最大值。 |
| static auto [Min](./min/)(T0, T1) | 返回两个指定数值中的最小值。 |
| static T0 [Min](./min/)(T0, T1) | 返回两个指定数值中的最小值。 |
| **float** [Min_](./min_/)(**float**, **float**) | 返回两个指定的单精度浮点数中的最小值。 |
| **double** [Min_](./min_/)(**double**, **double**) | 返回两个指定的双精度浮点数中的最小值。 |
| static T [Modulus](./modulus/)(T, T) | 计算一个指定值除以另一个指定值的余数。 |
| static **double** [Pow](./pow/)(**double**, **double**) | 返回指定值的指定次幂。 |
| static **double** [Round](./round/)(**double**) | 将指定值四舍五入为最近的整数值。 |
| static **double** [Round](./round/)(**double**, int) | 将指定值四舍五入为具有指定小数位数的最近值。 |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为最近的整数。若指定值恰好等距于两个最近整数，则由参数指定函数的行为。 |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为具有指定小数位数的最近值。若指定值恰好等距于两个最近值，则由参数指定函数的行为。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | 将指定值四舍五入为最近的整数值。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | 将指定值四舍五入为具有指定小数位数的最近值。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为最近的整数。若指定值恰好等距于两个最近整数，则由参数指定函数的行为。 |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为具有指定小数位数的最近值。若指定值恰好等距于两个最近值，则由参数指定函数的行为。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 确定指定有符号整数值的符号。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 确定指定浮点数值的符号。 |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | 确定指定十进制值的符号。 |
| static **double** [Sin](./sin/)(**double**) | 计算指定值的正弦。 |
| static **double** [Sinh](./sinh/)(**double**) | 计算指定值的双曲正弦。 |
| static **double** [Sqrt](./sqrt/)(**double**) | 返回指定值的平方根。 |
| static **double** [Tan](./tan/)(**double**) | 计算指定值的正切。 |
| static **double** [Tanh](./tanh/)(**double**) | 计算指定值的双曲正切。 |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | 返回表示一个值的 [Decimal](../decimal/) 对象，该值的整数部分等于由指定 [Decimal](../decimal/) 对象表示的值的整数部分，且所有小数位均被丢弃。 |
| static **double** [Truncate](./truncate/)(**double**) | 返回一个双精度浮点数，其整数部分等于指定值的整数部分，所有小数位均被丢弃。 |

## 字段

| Field | Description |
| --- | --- |
| static [E](./e/) | 自然对数的底数。 |
| static [NaN](./nan/) | 表示非数字 (NaN) 值。 |
| static [NegativeInfinity](./negativeinfinity/) | 表示负无穷大。 |
| static [PI](./pi/) | π 常数。 |
| static [PositiveInfinity](./positiveinfinity/) | 表示正无穷大。 |

## 备注



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // 打印绝对值。
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // 打印 PI/2 的正弦和 PI 的余弦。
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)