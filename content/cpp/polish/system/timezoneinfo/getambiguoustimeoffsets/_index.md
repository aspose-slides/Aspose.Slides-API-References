---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera daty i godziny UTC, do których może być przypisana określona data i godzina.
type: docs
weight: 261
url: /pl/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const metoda

Pobiera daty i godziny UTC, do których może być przypisana określona data i godzina.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data i godzina. |

### Wartość zwracana

[Array](../../array/) dat UTC i godzin.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const metoda

Pobiera daty i godziny UTC, do których może być przypisana określona data i godzina.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data i godzina. |

### Wartość zwracana

[Array](../../array/) dat UTC i godzin.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [TimeSpan](../../timespan/)
* Klasa [DateTime](../../datetime/)
* Klasa [TimeZoneInfo](../)
* Klasa [DateTimeOffset](../../datetimeoffset/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)