---
title: CreateCustomTimeZone()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy niestandardową strefę czasową.
type: docs
weight: 105
url: /pl/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) method

Tworzy niestandardową strefę czasową.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identyfikator strefy czasowej. |
| base_utc_offset | [TimeSpan](../../timespan/) | Przedział czasu pomiędzy standardowym czasem bieżącej strefy a czasem UTC. |
| display_name | const [String](../../string/)\& | Nazwa wyświetlana. |
| standard_display_name | const [String](../../string/)\& | Nazwa standardowego czasu. |
| daylight_display_name | const [String](../../string/)\& | Nazwa czasu letniego. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) reguł dostosowania. |
| disable_daylight_saving_time | **bool** | True, aby odrzucić wszelkie informacje o czasie letnim zawarte w adjustment_rules. |

### Wartość zwracana

Nowa strefa czasowa.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) method

Tworzy niestandardową strefę czasową.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identyfikator strefy czasowej. |
| base_utc_offset | [TimeSpan](../../timespan/) | Przedział czasu pomiędzy standardowym czasem bieżącej strefy a czasem UTC. |
| display_name | const [String](../../string/)\& | Nazwa wyświetlana. |
| standard_display_name | const [String](../../string/)\& | Nazwa standardowego czasu. |
| daylight_display_name | const [String](../../string/)\& | Nazwa czasu letniego. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) reguł dostosowania. |

### Wartość zwracana

Nowa strefa czasowa.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) method

Tworzy niestandardową strefę czasową.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | const [String](../../string/)\& | Identyfikator strefy czasowej. |
| base_utc_offset | [TimeSpan](../../timespan/) | Przedział czasu pomiędzy standardowym czasem bieżącej strefy a czasem UTC. |
| display_name | const [String](../../string/)\& | Nazwa wyświetlana. |
| standard_display_name | const [String](../../string/)\& | Nazwa standardowego czasu. |

### Wartość zwracana

Nowa strefa czasowa.

## Zobacz także

* Definicja typu [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Definicja typu [ArrayPtr](../../arrayptr/)
* Definicja typu [AdjustmentRulePtr](../adjustmentruleptr/)
* Klasa [String](../../string/)
* Klasa [TimeSpan](../../timespan/)
* Klasa [TimeZoneInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)