---
title: IsDaylightSavingTime()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻がサマータイムの範囲に該当するかを確認します。
type: docs
weight: 326
url: /ja/system/timezoneinfo/isdaylightsavingtime/
---
## TimeZoneInfo::IsDaylightSavingTime(DateTime) const メソッド

指定された日時がサマータイムの範囲に該当するかを確認します。

```cpp
bool System::TimeZoneInfo::IsDaylightSavingTime(DateTime date_time) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日時。 |

### 戻り値

date_time がサマータイムである場合は True。

## TimeZoneInfo::IsDaylightSavingTime(const DateTimeOffset\&) const メソッド

指定された日時がサマータイムの範囲に該当するかを確認します。

```cpp
bool System::TimeZoneInfo::IsDaylightSavingTime(const DateTimeOffset &date_time_offset) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日時。 |

### 戻り値

date_time がサマータイムである場合は True。

## 参照

* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)