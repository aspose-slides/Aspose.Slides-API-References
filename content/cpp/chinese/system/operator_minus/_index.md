---
title: operator-()
second_title: Aspose.Slides for C++ API 参考
description: 计算两个星期几之间的天数。
type: docs
weight: 2146
url: /zh/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) 函数


计算两个星期几之间的天数。

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | 被减数 |
| b | [DayOfWeek](../dayofweek/) | 减数 |

### 返回值

weekday **a** 和 **b** 之间的天数；如果*goes*在****之后，返回值为负数。

## System::operator-(const T\&, const Decimal\&) 函数


返回一个新的 [Decimal](../decimal/) 类实例，表示从指定的 [Decimal](../decimal/) 对象中减去指定值后得到的值。

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| x | const T\& | 被减值 |
| d | const [Decimal](../decimal/)\& | 表示被减值的 [Decimal](../decimal/) 对象 |

### 返回值

一个新的 [Decimal](../decimal/) 类实例，表示从 **x** 中减去 **d** 后的值。

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 函数


从左侧委托的回调列表末尾断开右侧委托的所有回调。

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | 将从中移除回调的委托。 |
| rhv | MulticastDelegate\<T\> | 其回调将被移除的委托。 |

### 返回值

返回一个委托，其中包含左侧值的回调，但不包含右侧值的回调。

## System::operator-(const T1\&, const Nullable\<T2\>\&) 函数


对非可空值和可空值进行相减。

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### 模板参数

| 参数 | 说明 |
| --- | --- |
| T1 | 左操作数类型。 |
| T2 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| some | const T1\& | 左操作数。 |
| other | const [Nullable](../nullable/)\<T2\>\& | 右操作数。 |

### 返回值

减法结果。

## 参见

* 枚举 [DayOfWeek](../dayofweek/)
* 类 [Decimal](../decimal/)
* 类 [Nullable](../nullable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)