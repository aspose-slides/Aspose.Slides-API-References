---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides C++ API 参考
description: 将时间转换为指定时区的时间。
type: docs
weight: 53
url: /zh/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) 方法

[Convert](../../convert/) 将时间转换为指定时区的时间。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要转换的日期和时间。 |
| destination_time_zone_id | const [String](../../string/)\& | 目标时区的标识符。 |

### 返回值

转换后的日期和时间。

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) 方法

[Convert](../../convert/) 将时间转换为指定时区的时间。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 要转换的日期和时间。 |
| destination_time_zone_id | const [String](../../string/)\& | 目标时区的标识符。 |

### 返回值

转换后的日期和时间。

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) 方法

[Convert](../../convert/) 将时间转换为指定时区的时间。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要转换的日期和时间。 |
| source_time_zone_id | const [String](../../string/)\& | 源时区的标识符。 |
| destination_time_zone_id | const [String](../../string/)\& | 目标时区的标识符。 |

### 返回值

转换后的日期和时间。

## 另请参见

* 类 [DateTime](../../datetime/)
* 类 [String](../../string/)
* 类 [TimeZoneInfo](../)
* 类 [DateTimeOffset](../../datetimeoffset/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)