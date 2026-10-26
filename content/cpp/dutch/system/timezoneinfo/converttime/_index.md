---
title: ConvertTime()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteer tijd van de ene tijdzone naar de andere.
type: docs
weight: 40
url: /nl/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) methode

[Convert](../../convert/) tijd van de ene tijdzone naar de andere.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum en tijd om te converteren. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Bron tijdzone. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Doel tijdzone. |

### Retourwaarde

Geconverteerde datum en tijd.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) methode

[Convert](../../convert/) tijd naar de tijd in een opgegeven tijdzone.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum en tijd om te converteren. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Doel tijdzone. |

### Retourwaarde

Geconverteerde datum en tijd.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) methode

[Convert](../../convert/) tijd naar de tijd in een opgegeven tijdzone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum en tijd om te converteren. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Doel tijdzone. |

### Retourwaarde

Geconverteerde datum en tijd.

## Zie ook

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Klasse [DateTime](../../datetime/)
* Klasse [TimeZoneInfo](../)
* Klasse [DateTimeOffset](../../datetimeoffset/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)