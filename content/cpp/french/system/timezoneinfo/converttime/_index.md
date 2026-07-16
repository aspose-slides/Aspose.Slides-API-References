---
title: ConvertTime()
second_title: Référence API Aspose.Slides pour C++
description: Convertir l'heure d'un fuseau horaire à un autre.
type: docs
weight: 40
url: /fr/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) méthode

[Convert](../../convert/) heure d'un fuseau horaire à un autre.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure à convertir. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuseau horaire source. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) méthode

[Convert](../../convert/) heure dans le fuseau horaire spécifié.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date et heure à convertir. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) méthode

[Convert](../../convert/) heure dans le fuseau horaire spécifié.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure à convertir. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Fuseau horaire de destination. |

### Valeur de retour

Date et heure converties.

## Voir aussi

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)