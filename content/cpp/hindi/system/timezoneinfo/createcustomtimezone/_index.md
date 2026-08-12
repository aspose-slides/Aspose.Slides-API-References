---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक कस्टम टाइम ज़ोन बनाता है।
type: docs
weight: 105
url: /hi/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method


एक कस्टम समय क्षेत्र बनाता है।

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | const [String](../../string/)\& | समय क्षेत्र पहचानकर्ता। |
| base_utc_offset | [TimeSpan](../../timespan/) | वर्तमान समय क्षेत्र के मानक समय और UTC समय के बीच का अंतराल। |
| display_name | const [String](../../string/)\& | डिस्प्ले नाम। |
| standard_display_name | const [String](../../string/)\& | मानक समय नाम। |
| daylight_display_name | const [String](../../string/)\& | डेलाइट सेविंग टाइम नाम। |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) समायोजन नियमों का। |
| disable_daylight_saving_time | **bool** | True to discard any daylight saving time information present in adjustment_rules. |

### रिटर्न वैल्यू

नया समय क्षेत्र।

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method


एक कस्टम समय क्षेत्र बनाता है।

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | const [String](../../string/)\& | समय क्षेत्र पहचानकर्ता। |
| base_utc_offset | [TimeSpan](../../timespan/) | वर्तमान समय क्षेत्र के मानक समय और UTC समय के बीच का अंतराल। |
| display_name | const [String](../../string/)\& | डिस्प्ले नाम। |
| standard_display_name | const [String](../../string/)\& | मानक समय नाम। |
| daylight_display_name | const [String](../../string/)\& | डेलाइट सेविंग टाइम नाम। |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) समायोजन नियमों का। |

### रिटर्न वैल्यू

नया समय क्षेत्र।

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method


एक कस्टम समय क्षेत्र बनाता है।

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | const [String](../../string/)\& | समय क्षेत्र पहचानकर्ता। |
| base_utc_offset | [TimeSpan](../../timespan/) | वर्तमान समय क्षेत्र के मानक समय और UTC समय के बीच का अंतराल। |
| display_name | const [String](../../string/)\& | डिस्प्ले नाम। |
| standard_display_name | const [String](../../string/)\& | मानक समय नाम। |

### रिटर्न वैल्यू

नया समय क्षेत्र।

## संदर्भ

* टाइपडिफ [TimeZoneInfoPtr](../../timezoneinfoptr/)
* टाइपडिफ [ArrayPtr](../../arrayptr/)
* टाइपडिफ [AdjustmentRulePtr](../adjustmentruleptr/)
* क्लास [String](../../string/)
* क्लास [TimeSpan](../../timespan/)
* क्लास [TimeZoneInfo](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)