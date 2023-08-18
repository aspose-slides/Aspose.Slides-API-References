---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a custom time zone.
type: docs
weight: 105
url: /system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Time zone identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Time interval between the current time zone's standard time and UTC time. |
| display_name | const [String](../../string/)\& | Display name. |
| standard_display_name | const [String](../../string/)\& | Standard time name. |
| daylight_display_name | const [String](../../string/)\& | Daylight saving time name. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) of adjustment rules. |
| disable_daylight_saving_time | **bool** | True to discard any daylight saving time information present in adjustment_rules. |

### Return Value

New time zone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Time zone identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Time interval between the current time zone's standard time and UTC time. |
| display_name | const [String](../../string/)\& | Display name. |
| standard_display_name | const [String](../../string/)\& | Standard time name. |
| daylight_display_name | const [String](../../string/)\& | Daylight saving time name. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) of adjustment rules. |

### Return Value

New time zone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


Creates a custom time zone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Time zone identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Time interval between the current time zone's standard time and UTC time. |
| display_name | const [String](../../string/)\& | Display name. |
| standard_display_name | const [String](../../string/)\& | Standard time name. |

### Return Value

New time zone.

## See Also

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Class [String](../../string/)
* Class [TimeSpan](../../timespan/)
* Class [TimeZoneInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)