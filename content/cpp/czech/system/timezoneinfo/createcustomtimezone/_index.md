---
title: CreateCustomTimeZone()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří vlastní časové pásmo.
type: docs
weight: 105
url: /cs/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

Vytvoří vlastní časové pásmo.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikátor časového pásma. |
| base_utc_offset | [TimeSpan](../../timespan/) | Časový interval mezi standardním časem aktuálního časového pásma a časem UTC. |
| display_name | const [String](../../string/)\& | Zobrazovaný název. |
| standard_display_name | const [String](../../string/)\& | Název standardního času. |
| daylight_display_name | const [String](../../string/)\& | Název letního času. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) pravidel úpravy. |
| disable_daylight_saving_time | **bool** | True, pokud chcete zahodit veškeré informace o letním čase obsažené v adjustment_rules. |

### Návratová hodnota

Nové časové pásmo.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

Vytvoří vlastní časové pásmo.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikátor časového pásma. |
| base_utc_offset | [TimeSpan](../../timespan/) | Časový interval mezi standardním časem aktuálního časového pásma a časem UTC. |
| display_name | const [String](../../string/)\& | Zobrazovaný název. |
| standard_display_name | const [String](../../string/)\& | Název standardního času. |
| daylight_display_name | const [String](../../string/)\& | Název letního času. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) pravidel úpravy. |

### Návratová hodnota

Nové časové pásmo.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

Vytvoří vlastní časové pásmo.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identifikátor časového pásma. |
| base_utc_offset | [TimeSpan](../../timespan/) | Časový interval mezi standardním časem aktuálního časového pásma a časem UTC. |
| display_name | const [String](../../string/)\& | Zobrazovaný název. |
| standard_display_name | const [String](../../string/)\& | Název standardního času. |

### Návratová hodnota

Nové časové pásmo.

## Viz také

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Třída [String](../../string/)
* Třída [TimeSpan](../../timespan/)
* Třída [TimeZoneInfo](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)