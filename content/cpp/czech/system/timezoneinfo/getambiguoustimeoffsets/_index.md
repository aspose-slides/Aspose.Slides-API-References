---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides pro C++ referenční příručka
description: Vrací data a časy UTC, na které lze mapovat zadané datum a čas.
type: docs
weight: 261
url: /cs/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const metoda

Získá data a časy UTC, na které lze mapovat zadané datum a čas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas. |

### Návratová hodnota

[Array](../../array/) UTC dat a časů.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const metoda

Získá data a časy UTC, na které lze mapovat zadané datum a čas.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum a čas. |

### Návratová hodnota

[Array](../../array/) UTC dat a časů.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [TimeSpan](../../timespan/)
* Třída [DateTime](../../datetime/)
* Třída [TimeZoneInfo](../)
* Třída [DateTimeOffset](../../datetimeoffset/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)