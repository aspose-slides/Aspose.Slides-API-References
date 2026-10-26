---
title: operator-()
second_title: Aspose.Slides C++ API 参考
description: 返回一个新的 DateTimeOffset 类实例，表示从当前对象所代表的值中减去指定时间间隔后得到的日期和时间值。
type: docs
weight: 521
url: /zh/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const 方法


返回一个新的 [DateTimeOffset](../) 类实例，表示从当前对象所代表的值中减去指定时间间隔后的日期和时间值。

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 要减去的时间间隔 |

### 返回值

返回一个新的 [DateTimeOffset](../) 类实例，表示从当前对象所代表的值中减去 **value** 后的日期和时间值。

## DateTimeOffset::operator-(const DateTimeOffset\&) const 方法


返回一个 [TimeSpan](../../timespan/) 类实例，表示当前对象和指定对象所代表的日期和时间值之间的时间间隔。

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | 一个 [DateTime](../../datetime/) 类实例，标记要计算的时间间隔的一端 |

### 返回值

返回一个 [TimeSpan](../../timespan/) 类实例，表示当前对象和 **other** 所代表的日期和时间值之间的时间间隔。

## 另请参阅

* 类 [DateTimeOffset](../)
* 类 [TimeSpan](../../timespan/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)