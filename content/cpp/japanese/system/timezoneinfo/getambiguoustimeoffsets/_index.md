---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻に対応付けられる UTC 日付と時刻を取得します。
type: docs
weight: 261
url: /ja/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const メソッド

指定された日時に対応付けられる UTC 日付と時刻を取得します。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日付と時刻。 |

### 戻り値

[Array](../../array/) の UTC 日付と時刻。

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const メソッド

指定された日時に対応付けられる UTC 日付と時刻を取得します。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日付と時刻。 |

### 戻り値

[Array](../../array/) の UTC 日付と時刻。

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [TimeSpan](../../timespan/)
* クラス [DateTime](../../datetime/)
* クラス [TimeZoneInfo](../)
* クラス [DateTimeOffset](../../datetimeoffset/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)