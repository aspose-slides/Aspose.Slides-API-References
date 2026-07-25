---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API リファレンス
description: カスタムタイムゾーンを作成します。
type: docs
weight: 105
url: /ja/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) メソッド

カスタムタイムゾーンを作成します。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | タイムゾーンの識別子。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 現在のタイムゾーンの標準時間と UTC 時間との差分。 |
| display_name | const [String](../../string/)\& | 表示名。 |
| standard_display_name | const [String](../../string/)\& | 標準時間の名前。 |
| daylight_display_name | const [String](../../string/)\& | サマータイムの名前。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) の調整規則。 |
| disable_daylight_saving_time | **bool** | adjustment_rules に含まれるサマータイム情報を破棄する場合は true。 |

### 戻り値

新しいタイムゾーン。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) メソッド

カスタムタイムゾーンを作成します。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | タイムゾーンの識別子。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 現在のタイムゾーンの標準時間と UTC 時間との差分。 |
| display_name | const [String](../../string/)\& | 表示名。 |
| standard_display_name | const [String](../../string/)\& | 標準時間の名前。 |
| daylight_display_name | const [String](../../string/)\& | サマータイムの名前。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) の調整規則。 |

### 戻り値

新しいタイムゾーン。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) メソッド

カスタムタイムゾーンを作成します。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | const [String](../../string/)\& | タイムゾーンの識別子。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 現在のタイムゾーンの標準時間と UTC 時間との差分。 |
| display_name | const [String](../../string/)\& | 表示名。 |
| standard_display_name | const [String](../../string/)\& | 標準時間の名前。 |

### 戻り値

新しいタイムゾーン。

## 参照

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* クラス [String](../../string/)
* クラス [TimeSpan](../../timespan/)
* クラス [TimeZoneInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)