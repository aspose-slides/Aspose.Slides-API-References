---
title: CreateCustomTimeZone()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نطاقًا زمنيًا مخصصًا.
type: docs
weight: 105
url: /ar/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) طريقة

ينشئ نطاقًا زمنيًا مخصصًا.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | const [String](../../string/)\& | معرف النطاق الزمني. |
| base_utc_offset | [TimeSpan](../../timespan/) | الفاصل الزمني بين الوقت القياسي للنطاق الزمني الحالي والوقت بالتوقيت العالمي UTC. |
| display_name | const [String](../../string/)\& | اسم العرض. |
| standard_display_name | const [String](../../string/)\& | اسم الوقت القياسي. |
| daylight_display_name | const [String](../../string/)\& | اسم التوقيت الصيفي. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) من قواعد التعديل. |
| disable_daylight_saving_time | **bool** | صحيح لتجاهل أي معلومات توقيت صيفي موجودة في adjustment_rules. |

### قيمة الإرجاع

نطاق زمني جديد.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) طريقة

ينشئ نطاقًا زمنيًا مخصصًا.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | const [String](../../string/)\& | معرف النطاق الزمني. |
| base_utc_offset | [TimeSpan](../../timespan/) | الفاصل الزمني بين الوقت القياسي للنطاق الزمني الحالي والوقت بالتوقيت العالمي UTC. |
| display_name | const [String](../../string/)\& | اسم العرض. |
| standard_display_name | const [String](../../string/)\& | اسم الوقت القياسي. |
| daylight_display_name | const [String](../../string/)\& | اسم التوقيت الصيفي. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) من قواعد التعديل. |

### قيمة الإرجاع

نطاق زمني جديد.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) طريقة

ينشئ نطاقًا زمنيًا مخصصًا.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | const [String](../../string/)\& | معرف النطاق الزمني. |
| base_utc_offset | [TimeSpan](../../timespan/) | الفاصل الزمني بين الوقت القياسي للنطاق الزمني الحالي والوقت بالتوقيت العالمي UTC. |
| display_name | const [String](../../string/)\& | اسم العرض. |
| standard_display_name | const [String](../../string/)\& | اسم الوقت القياسي. |

### قيمة الإرجاع

نطاق زمني جديد.

## انظر أيضًا

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* فئة [String](../../string/)
* فئة [TimeSpan](../../timespan/)
* فئة [TimeZoneInfo](../)
* نطاق [System](../../)
* Library [Aspose.Slides](../../../)