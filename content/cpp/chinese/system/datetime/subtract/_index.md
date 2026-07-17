---
title: Subtract()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 DateTime 类的新实例，表示从当前对象表示的值中减去指定时间间隔后的日期和时间值。
type: docs
weight: 326
url: /zh/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const 方法

返回一个 [DateTime](../) 类的新实例，表示从当前对象表示的值中减去指定时间间隔后的日期和时间值。

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | 要减去的时间间隔 |

### 返回值

返回一个 [DateTime](../) 类的新实例，表示从当前对象表示的值中减去 **duration** 后的日期和时间值。

## DateTime::Subtract(DateTime) const 方法

返回一个 [TimeSpan](../../timespan/) 类的实例，表示当前对象和指定对象所代表的日期和时间值之间的时间间隔。

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) 类的实例，标记要计算的间隔的一端 |

### 返回值

返回一个 [TimeSpan](../../timespan/) 类的实例，表示当前对象和 **value** 所代表的日期和时间值之间的时间间隔。

## 另请参见

* 类 [DateTime](../)
* 类 [TimeSpan](../../timespan/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)