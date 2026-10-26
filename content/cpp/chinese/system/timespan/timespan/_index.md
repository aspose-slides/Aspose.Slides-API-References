---
title: TimeSpan()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个表示零时间间隔的 TimeSpan 对象。
type: docs
weight: 1
url: /zh/system/timespan/timespan/
---
## TimeSpan::TimeSpan() 构造函数

构造一个表示零时间间隔的 [TimeSpan](../) 对象。

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) 构造函数

构造一个 [TimeSpan](../) 类的实例，表示指定的时间间隔。

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ticks | **int64_t** | 要由正在构造的实例表示的时间间隔，以 100 纳秒间隔的数量表示。 |

## TimeSpan::TimeSpan(int, int, int) 构造函数

构造一个 [TimeSpan](../) 类的实例，表示等于指定小时、分钟和秒数之和的时间间隔。

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hours | int | 实例所表示的时间间隔的小时部分中的小时数 |
| minutes | int | 实例所表示的时间间隔的分钟部分中的分钟数 |
| seconds | int | 实例所表示的时间间隔的秒数部分中的秒数 |

## TimeSpan::TimeSpan(int, int, int, int, int) 构造函数

构造一个 [TimeSpan](../) 类的实例，表示等于指定小时、分钟、秒和毫秒之和的时间间隔。

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| days | int | 实例所表示的时间间隔的天数部分中的天数 |
| hours | int | 实例所表示的时间间隔的小时部分中的小时数 |
| minutes | int | 实例所表示的时间间隔的分钟部分中的分钟数 |
| seconds | int | 实例所表示的时间间隔的秒数部分中的秒数 |
| milliseconds | int | 实例所表示的时间间隔的毫秒部分中的毫秒数 |

## TimeSpan::TimeSpan(const TimeSpan\&) 构造函数

构造一个表示等于由指定 [TimeSpan](../) 对象表示的时间间隔的 [TimeSpan](../) 对象。

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## 另请参见

* 类 [TimeSpan](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)