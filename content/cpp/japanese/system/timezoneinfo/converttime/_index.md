---
title: ConvertTime()
second_title: Aspose.Slides for C++ API リファレンス
description: あるタイムゾーンから別のタイムゾーンへ時間を変換します。
type: docs
weight: 40
url: /ja/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) あるタイムゾーンから別のタイムゾーンへの時間を変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換対象の日時。 |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 元のタイムゾーン。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 変換先のタイムゾーン。 |

### 戻り値

変換後の日時。

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) 指定されたタイムゾーンの時間に変換します。

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 変換対象の日時。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 変換先のタイムゾーン。 |

### 戻り値

変換後の日時。

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) method

[Convert](../../convert/) 指定されたタイムゾーンの時間に変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換対象の日時。 |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 変換先のタイムゾーン。 |

### 戻り値

変換後の日時。

## 参照

* 型定義 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)