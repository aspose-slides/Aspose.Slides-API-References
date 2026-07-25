---
title: ConvertTimeToUtc()
second_title: Aspose.Slides for C++ API リファレンス
description: 時間を UTC 時間に変換します。
type: docs
weight: 79
url: /ja/system/timezoneinfo/converttimetoutc/
---
## TimeZoneInfo::ConvertTimeToUtc(DateTime, const TimeZoneInfoPtr&) メソッド

時間を UTC 時間に変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeToUtc(DateTime date_time, const TimeZoneInfoPtr &source_time_zone)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換する日付と時刻。 |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | 元のタイムゾーン。 |

### 戻り値

変換された日付と時刻。

## TimeZoneInfo::ConvertTimeToUtc(DateTime) メソッド

時間を UTC 時間に変換します。

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeToUtc(DateTime date_time)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 変換する日付と時刻。 |

### 戻り値

変換された日付と時刻。

## 関連項目

* 型定義 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)