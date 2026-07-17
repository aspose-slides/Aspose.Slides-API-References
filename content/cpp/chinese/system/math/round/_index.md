---
title: Round()
second_title: Aspose.Slides for C++ API 参考
description: 将指定值四舍五入到最近的整数值。
type: docs
weight: 157
url: /zh/system/math/round/
---
## Math::Round(double) 方法

将指定值四舍五入到最近的整数值。

```cpp
static double System::Math::Round(double a)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | **double** | 要四舍五入的值 |

### 返回值

**a** 四舍五入到最近的整数值

## Math::Round(double, int) 方法

将指定值四舍五入到具有指定小数位数的最近值。

```cpp
static double System::Math::Round(double value, int digits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要四舍五入的值 |
| digits | int | 四舍五入后值的小数位数 |

### 返回值

最接近 **value** 的、具有指定位数的数字

## Math::Round(double, MidpointRounding) 方法

将指定值四舍五入到最近的整数。参数指定当指定值与两个最近的数等距时函数的行为。

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要四舍五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **value** 与两个最近的数等距时如何执行四舍五入。 |

### 返回值

**value** 四舍五入到最近的整数值

## Math::Round(double, int, MidpointRounding) 方法

将指定值四舍五入到具有指定小数位数的最近值。参数指定当指定值与两个最近的数等距时函数的行为。

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **double** | 要四舍五入的值 |
| digits | int | 四舍五入后值的小数位数 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **value** 与两个最近的数等距时如何执行四舍五入。 |

### 返回值

最接近 **value** 的、具有指定位数的数字

## Math::Round(const Decimal\&) 方法

将指定值四舍五入到最近的整数值。

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四舍五入的值 |

### 返回值

**d** 四舍五入到最近的整数值

## Math::Round(const Decimal\&, int) 方法

将指定值四舍五入到具有指定小数位数的最近值。

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 要四舍五入的值 |
| digits | int | 四舍五入后值的小数位数 |

### 返回值

最接近 **value** 的、具有指定位数的数字

## Math::Round(const Decimal\&, MidpointRounding) 方法

将指定值四舍五入到最近的整数。参数指定当指定值与两个最近的数等距时函数的行为。

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四舍五入的值 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **value** 与两个最近的数等距时如何执行四舍五入。 |

### 返回值

**d** 四舍五入到最近的整数值

## Math::Round(const Decimal\&, int, MidpointRounding) 方法

将指定值四舍五入到具有指定小数位数的最近值。参数指定当指定值与两个最近的数等距时函数的行为。

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | 要四舍五入的值 |
| digits | int | 四舍五入后值的小数位数 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定当 **value** 与两个最近的数等距时如何执行四舍五入。 |

### 返回值

最接近 **value** 的、具有指定位数的数字

## 另请参见

* 枚举 [MidpointRounding](../../midpointrounding/)
* 类 [Decimal](../../decimal/)
* 结构体 [Math](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)