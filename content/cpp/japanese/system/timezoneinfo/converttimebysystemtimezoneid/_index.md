---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたタイムゾーンの時間に変換します。
type: docs
weight: 53
url: /ja/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method

[Convert](../../convert/) 指定されたタイムゾーンの時間に変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換対象の日付と時刻。 |
| destination_time_zone_id | const [String](../../string/)\& | 宛先タイムゾーンの識別子。 |

### 戻り値

変換された日付と時刻。

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method

[Convert](../../convert/) 指定されたタイムゾーンの時間に変換します。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 変換対象の日付と時刻。 |
| destination_time_zone_id | const [String](../../string/)\& | 宛先タイムゾーンの識別子。 |

### 戻り値

変換された日付と時刻。

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method

[Convert](../../convert/) 指定されたタイムゾーンの時間に変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換対象の日付と時刻。 |
| source_time_zone_id | const [String](../../string/)\& | ソースタイムゾーンの識別子。 |
| destination_time_zone_id | const [String](../../string/)\& | 宛先タイムゾーンの識別子。 |

### 戻り値

変換された日付と時刻。

## 参照

* クラス [DateTime](../../datetime/)
* クラス [String](../../string/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)