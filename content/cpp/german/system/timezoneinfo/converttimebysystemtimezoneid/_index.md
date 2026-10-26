---
title: ConvertTimeBySystemTimeZoneId()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Zeit in die Zeit einer angegebenen Zeitzone.
type: docs
weight: 53
url: /de/system/timezoneinfo/converttimebysystemtimezoneid/
---
## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&) Methode

[Convert](../../convert/) Zeit in die Zeit einer angegebenen Zeitzone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &destination_time_zone_id)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum und Uhrzeit, die konvertiert werden sollen. |
| destination_time_zone_id | const [String](../../string/)\& | Bezeichner der Zielzeitzone. |

### Rückgabewert

Konvertiertes Datum und Uhrzeit.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset&, const String&) Methode

[Convert](../../convert/) Zeit in die Zeit einer angegebenen Zeitzone.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(const DateTimeOffset &date_time_offset, const String &destination_time_zone_id)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Datum und Uhrzeit, die konvertiert werden sollen. |
| destination_time_zone_id | const [String](../../string/)\& | Bezeichner der Zielzeitzone. |

### Rückgabewert

Konvertiertes Datum und Uhrzeit.

## TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime, const String&, const String&) Methode

[Convert](../../convert/) Zeit in die Zeit einer angegebenen Zeitzone.

```cpp
static DateTime System::TimeZoneInfo::ConvertTimeBySystemTimeZoneId(DateTime date_time, const String &source_time_zone_id, const String &destination_time_zone_id)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum und Uhrzeit, die konvertiert werden sollen. |
| source_time_zone_id | const [String](../../string/)\& | Bezeichner der Quellzeitzone. |
| destination_time_zone_id | const [String](../../string/)\& | Bezeichner der Zielzeitzone. |

### Rückgabewert

Konvertiertes Datum und Uhrzeit.

## Siehe auch

* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [TimeZoneInfo](../)
* Klasse [DateTimeOffset](../../datetimeoffset/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)