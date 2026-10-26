---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides pour C++ Référence API
description: Récupère les dates et heures UTC auxquelles une date et une heure spécifiées peuvent être associées.
type: docs
weight: 261
url: /fr/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const méthode

Obtient les dates et heures UTC auxquelles une date et une heure spécifiées peuvent être associées.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date et heure. |

### Valeur de retour

[Array](../../array/) des dates et heures UTC.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const méthode

Obtient les dates et heures UTC auxquelles une date et une heure spécifiées peuvent être associées.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date et heure. |

### Valeur de retour

[Array](../../array/) des dates et heures UTC.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [TimeSpan](../../timespan/)
* Classe [DateTime](../../datetime/)
* Classe [TimeZoneInfo](../)
* Classe [DateTimeOffset](../../datetimeoffset/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)