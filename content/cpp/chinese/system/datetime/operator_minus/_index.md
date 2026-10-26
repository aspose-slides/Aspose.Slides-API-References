---
title: operator-()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 DateTime 类的新实例，表示从当前对象所表示的值中减去指定时间跨度后得到的日期和时间值。
type: docs
weight: 651
url: /zh/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const 方法

返回一个 [DateTime](../) 类的新实例，表示从当前对象所表示的值中减去指定的 TimeSpan 后得到的日期和时间值。

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 要减去的时间间隔 |

### 返回值

返回一个 [DateTime](../) 类的新实例，表示从当前对象所表示的值中减去 **value** 后得到的日期和时间值。

## DateTime::operator-(DateTime) const 方法

返回一个 [TimeSpan](../../timespan/) 类的实例，表示当前对象和指定对象之间的日期和时间值之间的时间间隔。

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../) | 标记要计算的区间一端的 [DateTime](../) 类的实例 |

### 返回值

返回一个 [TimeSpan](../../timespan/) 类的实例，表示当前对象和 **value** 之间的日期和时间值之间的时间间隔。

## 另见

* 类 [DateTime](../)
* 类 [TimeSpan](../../timespan/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)