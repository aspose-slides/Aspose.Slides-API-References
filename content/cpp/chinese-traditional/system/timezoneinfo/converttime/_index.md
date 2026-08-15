---
title: ConvertTime()
second_title: Aspose.Slides C++ API 參考手冊
description: 將時間從一個時區轉換到另一個時區。
type: docs
weight: 40
url: /zh-hant/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 時間從一個時區轉換到另一個時區。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要轉換的日期和時間。 |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 來源時區。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目標時區。 |

### 返回值

轉換後的日期和時間。

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 時間轉換為指定時區的時間。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 要轉換的日期和時間。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目標時區。 |

### 返回值

轉換後的日期和時間。

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) 方法

[Convert](../../convert/) 時間轉換為指定時區的時間。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要轉換的日期和時間。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 目標時區。 |

### 返回值

轉換後的日期和時間。

## 參見

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 類別 [DateTime](../../datetime/)
* 類別 [TimeZoneInfo](../)
* 類別 [DateTimeOffset](../../datetimeoffset/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)