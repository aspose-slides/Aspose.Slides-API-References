---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides for C++ API 參考
description: 取得可映射至特定日期和時間的 UTC 日期與時間。
type: docs
weight: 261
url: /zh-hant/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const 方法

取得可映射至特定日期和時間的 UTC 日期與時間。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期與時間。 |

### 回傳值

[Array](../../array/) 的 UTC 日期與時間。

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const 方法

取得可映射至特定日期和時間的 UTC 日期與時間。

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日期與時間。 |

### 回傳值

[Array](../../array/) 的 UTC 日期與時間。

## 參見

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [TimeSpan](../../timespan/)
* 類別 [DateTime](../../datetime/)
* 類別 [TimeZoneInfo](../)
* 類別 [DateTimeOffset](../../datetimeoffset/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)