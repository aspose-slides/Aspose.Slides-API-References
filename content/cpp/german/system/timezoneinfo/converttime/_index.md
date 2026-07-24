---
title: ConvertTime()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Zeit von einer Zeitzone in eine andere.
type: docs
weight: 40
url: /de/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) Methode

[Convert](../../convert/) Zeit von einer Zeitzone zu einer anderen.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Source time zone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Rückgabewert

Converted date and time.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) Methode

[Convert](../../convert/) Zeit in die Zeit in einer angegebenen Zeitzone.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Rückgabewert

Converted date and time.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) Methode

[Convert](../../convert/) Zeit in die Zeit in einer angegebenen Zeitzone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Date and time to convert. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Destination time zone. |

### Rückgabewert

Converted date and time.

## Siehe auch

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Klasse [DateTime](../../datetime/)
* Klasse [TimeZoneInfo](../)
* Klasse [DateTimeOffset](../../datetimeoffset/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)