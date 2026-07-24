---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt UTC-Daten und -Uhrzeiten, auf die ein angegebenes Datum und eine angegebene Uhrzeit abgebildet werden kann.
type: docs
weight: 261
url: /de/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const Methode

Ermittelt UTC-Daten und -Uhrzeiten, auf die ein angegebenes Datum und eine angegebene Uhrzeit abgebildet werden kann.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum und Uhrzeit. |

### Rückgabewert

[Array](../../array/) von UTC-Daten und -Uhrzeiten.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const Methode

Ermittelt UTC-Daten und -Uhrzeiten, auf die ein angegebenes Datum und eine angegebene Uhrzeit abgebildet werden kann.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum und Uhrzeit. |

### Rückgabewert

[Array](../../array/) von UTC-Daten und -Uhrzeiten.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [TimeSpan](../../timespan/)
* Klasse [DateTime](../../datetime/)
* Klasse [TimeZoneInfo](../)
* Klasse [DateTimeOffset](../../datetimeoffset/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)