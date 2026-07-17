---
title: ConvertTime()
second_title: Aspose.Slides for C++ API 参考
description: 将时间从一个时区转换到另一个时区。
type: docs
weight: 40
url: /zh/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 将时间从一个时区转换到另一个时区。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要转换的日期和时间。 |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 源时区。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目标时区。 |

### 返回值

已转换的日期和时间。

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 将时间转换为指定时区的时间。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 要转换的日期和时间。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目标时区。 |

### 返回值

已转换的日期和时间。

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 将时间转换为指定时区的时间。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要转换的日期和时间。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目标时区。 |

### 返回值

已转换的日期和时间。

## 另请参见

* 类型定义 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 类 [DateTime](../../datetime/)
* 类 [TimeZoneInfo](../)
* 类 [DateTimeOffset](../../datetimeoffset/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)