---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API 参考
description: 获取可以映射到的指定日期和时间的 UTC 日期和时间。
type: docs
weight: 261
url: /zh/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const 方法

获取可以映射到的指定日期和时间的 UTC 日期和时间。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和时间。 |

### 返回值

[Array](../../array/) 的 UTC 日期和时间。

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const 方法

获取可以映射到的指定日期和时间的 UTC 日期和时间。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日期和时间。 |

### 返回值

[Array](../../array/) 的 UTC 日期和时间。

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [TimeSpan](../../timespan/)
* 类 [DateTime](../../datetime/)
* 类 [TimeZoneInfo](../)
* 类 [DateTimeOffset](../../datetimeoffset/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)