---
title: CreateCustomTimeZone()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een aangepaste tijdzone.
type: docs
weight: 105
url: /nl/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

Creëert een aangepaste tijdzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tijdzone-identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tijdinterval tussen de standaardtijd van de huidige tijdzone en UTC-tijd. |
| display_name | const [String](../../string/)\& | Weergavenaam. |
| standard_display_name | const [String](../../string/)\& | Naam van de standaardtijd. |
| daylight_display_name | const [String](../../string/)\& | Naam van de zomertijd. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) van aanpassingsregels. |
| disable_daylight_saving_time | **bool** | True om alle zomertijd-informatie die aanwezig is in adjustment_rules te negeren. |

### Retourwaarde

Nieuwe tijdzone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

Creëert een aangepaste tijdzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tijdzone-identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tijdinterval tussen de standaardtijd van de huidige tijdzone en UTC-tijd. |
| display_name | const [String](../../string/)\& | Weergavenaam. |
| standard_display_name | const [String](../../string/)\& | Naam van de standaardtijd. |
| daylight_display_name | const [String](../../string/)\& | Naam van de zomertijd. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) van aanpassingsregels. |

### Retourwaarde

Nieuwe tijdzone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

Creëert een aangepaste tijdzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| id | const [String](../../string/)\& | Tijdzone-identifier. |
| base_utc_offset | [TimeSpan](../../timespan/) | Tijdinterval tussen de standaardtijd van de huidige tijdzone en UTC-tijd. |
| display_name | const [String](../../string/)\& | Weergavenaam. |
| standard_display_name | const [String](../../string/)\& | Naam van de standaardtijd. |

### Retourwaarde

Nieuwe tijdzone.

## Zie ook

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Klasse [String](../../string/)
* Klasse [TimeSpan](../../timespan/)
* Klasse [TimeZoneInfo](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)