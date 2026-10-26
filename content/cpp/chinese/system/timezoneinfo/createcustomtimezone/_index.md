---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API 参考
description: 创建自定义时区。
type: docs
weight: 105
url: /zh/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) 方法

创建自定义时区。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 时区标识符。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 当前时区的标准时间与 UTC 时间之间的时间间隔。 |
| display_name | const [String](../../string/)\& | 显示名称。 |
| standard_display_name | const [String](../../string/)\& | 标准时间名称。 |
| daylight_display_name | const [String](../../string/)\& | 夏令时名称。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 的调整规则。 |
| disable_daylight_saving_time | **bool** | True 以丢弃 adjustment_rules 中的任何夏令时信息。 |

### 返回值

新时区。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) 方法

创建自定义时区。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 时区标识符。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 当前时区的标准时间与 UTC 时间之间的时间间隔。 |
| display_name | const [String](../../string/)\& | 显示名称。 |
| standard_display_name | const [String](../../string/)\& | 标准时间名称。 |
| daylight_display_name | const [String](../../string/)\& | 夏令时名称。 |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) 的调整规则。 |

### 返回值

新时区。

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) 方法

创建自定义时区。

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | const [String](../../string/)\& | 时区标识符。 |
| base_utc_offset | [TimeSpan](../../timespan/) | 当前时区的标准时间与 UTC 时间之间的时间间隔。 |
| display_name | const [String](../../string/)\& | 显示名称。 |
| standard_display_name | const [String](../../string/)\& | 标准时间名称。 |

### 返回值

新时区。

## 参见

* 类型定义 [TimeZoneInfoPtr](../../timezoneinfoptr/)
* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [AdjustmentRulePtr](../adjustmentruleptr/)
* 类 [String](../../string/)
* 类 [TimeSpan](../../timespan/)
* 类 [TimeZoneInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)