---
title: CreateCustomTimeZone()
second_title: Aspose.Slides for C++ API-referencia
description: Egy egyedi időzónát hoz létre.
type: docs
weight: 105
url: /hu/system/timezoneinfo/createcustomtimezone/
---
## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&, bool) metódus


Egy egyedi időzónát hoz létre.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules, bool disable_daylight_saving_time)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | const [String](../../string/)\& | Időzóna-azonosító. |
| base_utc_offset | [TimeSpan](../../timespan/) | Az aktuális időzóna szabványos ideje és az UTC idő közötti időintervallum. |
| display_name | const [String](../../string/)\& | Megjelenített név. |
| standard_display_name | const [String](../../string/)\& | Szabványos idő neve. |
| daylight_display_name | const [String](../../string/)\& | Nyári időszámítás neve. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) az igazítási szabályok. |
| disable_daylight_saving_time | **bool** | Igaz, ha el kell dobni minden nyári időszámítási információt az adjustment_rules-ban. |

### Visszatérési érték

Új időzóna.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&, const String\&, const ArrayPtr\<AdjustmentRulePtr\>\&) metódus


Egy egyedi időzónát hoz létre.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name, const String &daylight_display_name, const ArrayPtr<AdjustmentRulePtr> &adjustment_rules)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | const [String](../../string/)\& | Időzóna-azonosító. |
| base_utc_offset | [TimeSpan](../../timespan/) | Az aktuális időzóna szabványos ideje és az UTC idő közötti időintervallum. |
| display_name | const [String](../../string/)\& | Megjelenített név. |
| standard_display_name | const [String](../../string/)\& | Szabványos idő neve. |
| daylight_display_name | const [String](../../string/)\& | Nyári időszámítás neve. |
| adjustment_rules | const [ArrayPtr](../../arrayptr/)\<[AdjustmentRulePtr](../adjustmentruleptr/)\>\& | [Array](../../array/) az igazítási szabályok. |

### Visszatérési érték

Új időzóna.

## TimeZoneInfo::CreateCustomTimeZone(const String\&, TimeSpan, const String\&, const String\&) metódus


Egy egyedi időzónát hoz létre.

```cpp
static TimeZoneInfoPtr System::TimeZoneInfo::CreateCustomTimeZone(const String &id, TimeSpan base_utc_offset, const String &display_name, const String &standard_display_name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | const [String](../../string/)\& | Időzóna-azonosító. |
| base_utc_offset | [TimeSpan](../../timespan/) | Az aktuális időzóna szabványos ideje és az UTC idő közötti időintervallum. |
| display_name | const [String](../../string/)\& | Megjelenített név. |
| standard_display_name | const [String](../../string/)\& | Szabványos idő neve. |

### Visszatérési érték

Új időzóna.

## Lásd még

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [AdjustmentRulePtr](../adjustmentruleptr/)
* Osztály [String](../../string/)
* Osztály [TimeSpan](../../timespan/)
* Osztály [TimeZoneInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)