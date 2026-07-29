---
title: GetAmbiguousTimeOffsets()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar UTC-datum och tider som ett angivet datum och en tid kan avbildas till.
type: docs
weight: 261
url: /sv/system/timezoneinfo/getambiguoustimeoffsets/
---
## TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime) const metod

Hämtar UTC-datum och -tider som ett angivet datum och en tid kan avbildas till.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(DateTime date_time) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid. |

### Returvärde

[Array](../../array/) av UTC-datum och -tider.

## TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset\&) const metod

Hämtar UTC-datum och -tider som ett angivet datum och en tid kan avbildas till.

```cpp
ArrayPtr<TimeSpan> System::TimeZoneInfo::GetAmbiguousTimeOffsets(const DateTimeOffset &date_time_offset) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum och tid. |

### Returvärde

[Array](../../array/) av UTC-datum och -tider.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [TimeSpan](../../timespan/)
* Klass [DateTime](../../datetime/)
* Klass [TimeZoneInfo](../)
* Klass [DateTimeOffset](../../datetimeoffset/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)