---
title: DateTimeOffset()
second_title: Aspose.Slides C++ API 参考
description: 默认构造函数。
type: docs
weight: 1
url: /zh/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor

默认构造函数。

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和时间。 |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ticks | **int64_t** | 滴答数。 |
| offset | [TimeSpan](../../timespan/) | 相对于 UTC 的时间偏移。 |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和时间。 |
| offset | [TimeSpan](../../timespan/) | 相对于 UTC 的时间偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 年份（1 到 9999）。 |
| month | int | 月份（1 到 12）。 |
| day | int | 日期（1 到该月的天数）。 |
| hour | int | 小时（0 到 23）。 |
| minute | int | 分钟（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| offset | [TimeSpan](../../timespan/) | 相对于 UTC 的时间偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 年份（1 到 9999）。 |
| month | int | 月份（1 到 12）。 |
| day | int | 日期（1 到该月的天数）。 |
| hour | int | 小时（0 到 23）。 |
| minute | int | 分钟（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| millisecond | int | 毫秒（0 到 999）。 |
| offset | [TimeSpan](../../timespan/) | 相对于 UTC 的时间偏移。 |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructor

构造函数。

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| year | int | 年份。 |
| month | int | 月份（1 到 12）。 |
| day | int | 日期（1 到该月的天数）。 |
| hour | int | 小时（0 到 23）。 |
| minute | int | 分钟（0 到 59）。 |
| second | int | 秒（0 到 59）。 |
| millisecond | int | 毫秒（0 到 999）。 |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | 用于解释年份、月份和日期的日历。 |
| offset | [TimeSpan](../../timespan/) | 相对于 UTC 的时间偏移。 |

## See Also

* 类型别名 [SharedPtr](../../sharedptr/)
* 类 [DateTimeOffset](../)
* 类 [DateTime](../../datetime/)
* 类 [TimeSpan](../../timespan/)
* 类 [Calendar](../../../system.globalization/calendar/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)