---
title: CreateCustomTimeZone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine benutzerdefinierte Zeitzone.
type: docs
weight: 105
url: /de/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) Methode

Erstellt eine benutzerdefinierte Zeitzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | const [String](../../string/)\& | Zeitzonenbezeichner. |
| base_utc_offset | [TimeSpan](../../timespan/) | Zeitintervall zwischen der Standardzeit der aktuellen Zeitzone und der UTC-Zeit. |
| display_name | const [String](../../string/)\& | Anzeigename. |
| standard_display_name | const [String](../../string/)\& | Standardzeitname. |
| daylight_display_name | const [String](../../string/)\& | Sommerzeitname. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) der Anpassungsregeln. |
| disable_daylight_saving_time | **bool** | Wahr, um alle in adjustment_rules enthaltenen Informationen zur Sommerzeit zu verwerfen. |

### Rückgabewert

Neue Zeitzone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) Methode

Erstellt eine benutzerdefinierte Zeitzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | const [String](../../string/)\& | Zeitzonenbezeichner. |
| base_utc_offset | [TimeSpan](../../timespan/) | Zeitintervall zwischen der Standardzeit der aktuellen Zeitzone und der UTC-Zeit. |
| display_name | const [String](../../string/)\& | Anzeigename. |
| standard_display_name | const [String](../../string/)\& | Standardzeitname. |
| daylight_display_name | const [String](../../string/)\& | Sommerzeitname. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) der Anpassungsregeln. |

### Rückgabewert

Neue Zeitzone.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) Methode


Erstellt eine benutzerdefinierte Zeitzone.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | const [String](../../string/)\& | Zeitzonenbezeichner. |
| base_utc_offset | [TimeSpan](../../timespan/) | Zeitintervall zwischen der Standardzeit der aktuellen Zeitzone und der UTC-Zeit. |
| display_name | const [String](../../string/)\& | Anzeigename. |
| standard_display_name | const [String](../../string/)\& | Standardzeitname. |

### Rückgabewert

Neue Zeitzone.

## Siehe auch

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Klasse [String](../../string/)
* Klasse [TimeSpan](../../timespan/)
* Klasse [TimeZoneInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)