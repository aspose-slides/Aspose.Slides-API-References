---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides for C++ API 參考
description: 將時間轉換為指定時區的時間。
type: docs
weight: 53
url: /zh-hant/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&) 方法

[Convert](../../convert/) 將時間轉換為指定時區的時間。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要轉換的日期和時間。 |
| destination_time_zone_id | const [String](../../string/)\& | 目標時區的識別碼。 |

### 返回值

Converted date and time.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String&) 方法


[Convert](../../convert/) 將時間轉換為指定時區的時間。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 要轉換的日期和時間。 |
| destination_time_zone_id | const [String](../../string/)\& | 目標時區的識別碼。 |

### 返回值

Converted date and time.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String&) 方法


[Convert](../../convert/) 將時間轉換為指定時區的時間。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 要轉換的日期和時間。 |
| source_time_zone_id | const [String](../../string/)\& | 來源時區的識別碼。 |
| destination_time_zone_id | const [String](../../string/)\& | 目標時區的識別碼。 |

### 返回值

Converted date and time.

## 另見

* 類別 [DateTime](../../datetime/)
* 類別 [String](../../string/)
* 類別 [TimeZoneInfo](../)
* 類別 [DateTimeOffset](../../datetimeoffset/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)