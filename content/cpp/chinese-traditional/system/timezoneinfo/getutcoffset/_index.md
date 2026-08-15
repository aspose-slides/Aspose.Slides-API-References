---
title: GetUtcOffset()
second_title: Aspose.Slides for C++ API 參考文件
description: 計算此時區與 UTC 時區在指定日期和時間之間的差異。
type: docs
weight: 274
url: /zh-hant/system/timezoneinfo/getutcoffset/
---
## TimeZoneInfo::GetUtcOffset(DateTime) const 方法


計算此時區與 UTC 時區在指定日期時間之間的差異。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(DateTime date_time) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | 日期和時間。 |

### 返回值

時區之間的時間差。

## TimeZoneInfo::GetUtcOffset(const DateTimeOffset\&) const 方法


計算此時區與 UTC 時區在指定日期時間之間的差異。

```cpp
TimeSpan System::TimeZoneInfo::GetUtcOffset(const DateTimeOffset &date_time_offset) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | 日期和時間。 |

### 返回值

時區之間的時間差。

## 另請參閱

* 類別 [TimeSpan](../../timespan/)
* 類別 [DateTime](../../datetime/)
* 類別 [TimeZoneInfo](../)
* 類別 [DateTimeOffset](../../datetimeoffset/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)