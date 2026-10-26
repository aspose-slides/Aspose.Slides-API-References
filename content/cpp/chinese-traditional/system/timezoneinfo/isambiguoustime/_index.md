---
title: IsAmbiguousTime()
second_title: Aspose.Slides for C++ API 參考
description: 檢查指定的日期和時間是否為模糊時間，且可以映射到多個 UTC 時間。
type: docs
weight: 313
url: /zh-hant/system/timezoneinfo/isambiguoustime/
---
## TimeZoneInfo::IsAmbiguousTime(DateTime) const 方法


檢查指定的日期和時間是否為模糊時間，且可能映射到多個 UTC 時間。

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(DateTime date_time) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和時間。 |

### 返回值

若 date_time 為模糊時間則返回 True。

## TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset\&) const 方法


檢查指定的日期和時間是否為模糊時間，且可能映射到多個 UTC 時間。

```cpp
bool System::TimeZoneInfo::IsAmbiguousTime(const DateTimeOffset &date_time_offset) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日期和時間。 |

### 返回值

若 date_time 為模糊時間則返回 True。

## 另請參閱

* 類別 [DateTime](../../datetime/)
* 類別 [TimeZoneInfo](../)
* 類別 [DateTimeOffset](../../datetimeoffset/)
* 名稱空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)