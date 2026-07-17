---
title: GetUtcOffset()
second_title: Aspose.Slides for C++ API 参考
description: 计算此时区的时间与 UTC 时区在指定日期和时间之间的差异。
type: docs
weight: 274
url: /zh/system/timezoneinfo/getutcoffset/
---
## TimeZoneInfo::GetUtcOffset(DateTime) const 方法

计算此时区的时间与 UTC 时区在指定日期和时间之间的差异。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(DateTime date_time) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和时间。 |

### 返回值

时区之间的时间差。

## TimeZoneInfo::GetUtcOffset(const DateTimeOffset\&) const 方法

计算此时区的时间与 UTC 时区在指定日期和时间之间的差异。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(const DateTimeOffset &date_time_offset) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日期和时间。 |

### 返回值

时区之间的时间差。

## 另见

* 类 [TimeSpan](../../timespan/)
* 类 [DateTime](../../datetime/)
* 类 [TimeZoneInfo](../)
* 类 [DateTimeOffset](../../datetimeoffset/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)