---
title: MathF
second_title: Aspose.Slides C++ API 参考
description: 包含单精度浮点值的数学函数。这是一个没有实例服务的静态类型。绝不要以任何方式创建其实例。
type: docs
weight: 1769
url: /zh/system/mathf/
---
## MathF 结构体

Contains math functions for single-precision floating-point values. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class MathF
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static T [Abs](./abs/)(T) | 返回指定值的绝对值。 |
| static **float** [Acos](./acos/)(**float**) | 计算指定值的反余弦。 |
| static **float** [Asin](./asin/)(**float**) | 计算指定值的反正弦。 |
| static **float** [Atan](./atan/)(**float**) | 计算指定值的反正切。 |
| static **float** [Atan2](./atan2/)(**float**, **float**) | 计算指定值的比率的反正切。 |
| static **float** [Ceiling](./ceiling/)(**float**) | 返回不小于指定值的最小整数值。 |
| static **float** [Cos](./cos/)(**float**) | 计算指定值的余弦。 |
| static **float** [Cosh](./cosh/)(**float**) | 计算指定值的双曲余弦。 |
| static **float** [Exp](./exp/)(**float**) | 返回 e 常数的指定次幂。 |
| static **float** [Floor](./floor/)(**float**) | 返回不大于指定值的最大整数值。 |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | 返回指定数除以另一个指定数的余数。 |
| static **float** [Log](./log/)(**float**) | 返回指定值的自然对数。 |
| static **float** [Log](./log/)(**float**, **float**) | 返回指定基数下指定值的对数。 |
| static **float** [Log10](./log10/)(**float**) | 返回指定值的以 10 为底的对数。 |
| static **float** [Pow](./pow/)(**float**, **float**) | 返回指定值的指定次幂。 |
| static **float** [Round](./round/)(**float**) | 将指定值四舍五入为最近的整数值。 |
| static **float** [Round](./round/)(**float**, int) | 将指定值四舍五入为指定小数位数的最近值。 |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为最近的整数。参数指定当指定值同等接近两个最近数时函数的行为。 |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为指定小数位数的最近值。参数指定当指定值同等接近两个最近数时函数的行为。 |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | 将指定值四舍五入为指定小数位数的最近值。参数指定当指定值同等接近两个最近数时函数的行为。 |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | 确定指定带符号整数值的符号。 |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | 确定指定浮点值的符号。 |
| static **float** [Sin](./sin/)(**float**) | 计算指定值的正弦。 |
| static **float** [Sinh](./sinh/)(**float**) | 计算指定值的双曲正弦。 |
| static **float** [Sqrt](./sqrt/)(**float**) | 返回指定值的平方根。 |
| static **float** [Tan](./tan/)(**float**) | 计算指定值的正切。 |
| static **float** [Tanh](./tanh/)(**float**) | 计算指定值的双曲正切。 |
| static **float** [Truncate](./truncate/)(**float**) | 返回一个单精度浮点值，其整数部分等于指定值并且所有小数位被舍弃。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [E](./e/) | 自然对数的底数。 |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | 圆周率常数。 |
| static [Tau](./tau/) | Tau 值。 |

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)