---
title: ConvertTimeBySystemTimeZoneId()
second_title: Référence API Aspose.Slides pour C++
description: Convertit le temps à l'heure dans un fuseau horaire spécifié.
type: docs
weight: 53
url: /fr/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&) method


[Convert](../../convert/) heure à l'heure dans un fuseau horaire spécifié.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure à convertir. |
| destination_time_zone_id | const [String](../../string/)\& | Identifiant du fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset\&, const String\&) method


[Convert](../../convert/) heure à l'heure dans un fuseau horaire spécifié.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date et heure à convertir. |
| destination_time_zone_id | const [String](../../string/)\& | Identifiant du fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String\&, const String\&) method


[Convert](../../convert/) heure à l'heure dans un fuseau horaire spécifié.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure à convertir. |
| source_time_zone_id | const [String](../../string/)\& | Identifiant du fuseau horaire source. |
| destination_time_zone_id | const [String](../../string/)\& | Identifiant du fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## Voir aussi

* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)