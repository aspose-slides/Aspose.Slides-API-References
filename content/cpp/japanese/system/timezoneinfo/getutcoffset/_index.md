---
title: GetUtcOffset()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻に対して、このタイムゾーンの時間と UTC タイムゾーンの時間との差を計算します。
type: docs
weight: 274
url: /ja/system/timezoneinfo/getutcoffset/
---
## TimeZoneInfo::GetUtcOffset(DateTime) const メソッド

指定された日付と時刻に対して、このタイムゾーンの時間と UTC タイムゾーンの時間との差を計算します。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(DateTime date_time) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日付と時刻。 |

### 戻り値

タイムゾーン間の時間差。

## TimeZoneInfo::GetUtcOffset(const DateTimeOffset\&) const メソッド

指定された日付と時刻に対して、このタイムゾーンの時間と UTC タイムゾーンの時間との差を計算します。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(const DateTimeOffset &date_time_offset) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日付と時刻。 |

### 戻り値

タイムゾーン間の時間差。

## 参照

* クラス [TimeSpan](../../timespan/)
* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)