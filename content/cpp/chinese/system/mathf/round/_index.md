---
title: Round()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的值四舍五入到最接近的整数值。
type: docs
weight: 157
url: /zh/system/mathf/round/
---
## MathF::Round(float) 方法

将指定的值四舍五入到最接近的整数值。

```cpp
static float System::MathF::Round(float a)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **float** | 要四舍五入的值 |

### 返回值

**a** 四舍五入到最接近的整数值

## MathF::Round(float, int) 方法

将指定的值四舍五入到具有指定小数位数的最近值。

```cpp
static float System::MathF::Round(float value, int digits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要四舍五入的值 |
| digits | int | 四舍后值的小数位数 |

### 返回值

具有指定小数位数的、最接近 **value** 的数

## MathF::Round(float, MidpointRounding) 方法

将指定的值四舍五入到最接近的整数。若指定的值同等接近两个最近的数字，则由参数指定函数的行为。

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要四舍五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 如果 **value** 同等接近两个最近的数字，指定如何执行四舍五入。 |

### 返回值

**value** 四舍五入到最接近的整数值

## MathF::Round(float, int, MidpointRounding) 方法

将指定的值四舍五入到具有指定小数位数的最近值。若指定的值同等接近两个最近的数字，则由参数指定函数的行为。

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **float** | 要四舍五入的值 |
| digits | int | 四舍后值的小数位数 |
| mode | [MidpointRounding](../../midpointrounding/) | 如果 **value** 同等接近两个最近的数字，指定如何执行四舍五入。 |

### 返回值

具有指定小数位数的、最接近 **value** 的数

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)