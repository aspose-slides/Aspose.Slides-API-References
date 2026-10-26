---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API 參考
description: 建立自訂時區。
type: docs
weight: 105
url: /zh-hant/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) 方法

建立自訂時區。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 時區識別碼。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 目前時區的標準時間與 UTC 時間之間的時間間隔。 |
| display_name | const [String](../../string/)\& | 顯示名稱。 |
| standard_display_name | const [String](../../string/)\& | 標準時間名稱。 |
| daylight_display_name | const [String](../../string/)\& | 夏令時間名稱。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 調整規則。 |
| disable_daylight_saving_time | **bool** | 若為 true，則捨棄 adjustment_rules 中的任何夏令時間資訊。 |

### 傳回值

新時區。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) 方法

建立自訂時區。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 時區識別碼。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 目前時區的標準時間與 UTC 時間之間的時間間隔。 |
| display_name | const [String](../../string/)\& | 顯示名稱。 |
| standard_display_name | const [String](../../string/)\& | 標準時間名稱。 |
| daylight_display_name | const [String](../../string/)\& | 夏令時間名稱。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 調整規則。 |

### 傳回值

新時區。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) 方法

建立自訂時區。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 時區識別碼。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 目前時區的標準時間與 UTC 時間之間的時間間隔。 |
| display_name | const [String](../../string/)\& | 顯示名稱。 |
| standard_display_name | const [String](../../string/)\& | 標準時間名稱。 |

### 傳回值

新時區。

## 另請參閱

* 型別定義 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 型別定義 [ArrayPtr](../../arrayptr/)
* 型別定義 [AdjustmentRulePtr](../adjustmentruleptr/)
* 類別 [String](../../string/)
* 類別 [TimeSpan](../../timespan/)
* 類別 [TimeZoneInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)