---
title: IsAmbiguousTime()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻が曖昧で、複数の UTC 時間にマッピングできるかどうかを確認します。
type: docs
weight: 313
url: /ja/system/timezoneinfo/isambiguoustime/
---
## TimeZoneInfo::IsAmbiguousTime(DateTime) const メソッド

指定された日付と時刻が曖昧で、複数の UTC 時間にマッピングできるかどうかを確認します。

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(DateTime date_time) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日付と時刻。 |

### 戻り値

True if date_time が曖昧な場合。

## TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset\&) const メソッド

指定された日付と時刻が曖昧で、複数の UTC 時間にマッピングできるかどうかを確認します。

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset &date_time_offset) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日付と時刻。 |

### 戻り値

True if date_time が曖昧な場合。

## 参照

* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)