---
title: CreateCustomTimeZone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en anpassad tidszon.
type: docs
weight: 105
url: /sv/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) metod

Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tidszonsidentifierare. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const [String](../../string/)\& | Visningsnamn. |
| standard_display_name | const [String](../../string/)\& | Standardtidsnamn. |
| daylight_display_name | const [String](../../string/)\& | Sommartidsnamn. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) av justeringsregler. |
| disable_daylight_saving_time | **bool** | True för att ignorera all sommartidsinformation som finns i adjustment_rules. |

### Returvärde

Ny tidszon.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) metod

Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tidszonsidentifierare. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const [String](../../string/)\& | Visningsnamn. |
| standard_display_name | const [String](../../string/)\& | Standardtidsnamn. |
| daylight_display_name | const [String](../../string/)\& | Sommartidsnamn. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) av justeringsregler. |

### Returvärde

Ny tidszon.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) metod

Skapar en anpassad tidszon.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tidszonsidentifierare. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tidsintervall mellan den aktuella tidszonens standardtid och UTC-tid. |
| display_name | const [String](../../string/)\& | Visningsnamn. |
| standard_display_name | const [String](../../string/)\& | Standardtidsnamn. |

### Returvärde

Ny tidszon.

## Se även

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Klass [String](../../string/)
* Klass [TimeSpan](../../timespan/)
* Klass [TimeZoneInfo](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)