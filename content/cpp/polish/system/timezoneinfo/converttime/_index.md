---
title: ConvertTime()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuj czas z jednej strefy czasowej na drugą.
type: docs
weight: 40
url: /pl/system/timezoneinfo/converttime/
---
## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&, const TimeZoneInfoPtr\&) metoda

[Convert](../../convert/) czas z jednej strefy czasowej do drugiej.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &source_time_zone, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data i godzina do konwersji. |
| source_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Źródłowa strefa czasowa. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Docelowa strefa czasowa. |

### Wartość zwracana

Przekształcona data i godzina.

## TimeZoneInfo::ConvertTime(const DateTimeOffset\&, const TimeZoneInfoPtr\&) metoda

[Convert](../../convert/) czas do czasu w określonej strefie czasowej.

```cpp
static DateTimeOffset System::TimeZoneInfo::ConvertTime(const DateTimeOffset &date_time_offset, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time_offset | const [DateTimeOffset](../../datetimeoffset/)\& | Data i godzina do konwersji. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Docelowa strefa czasowa. |

### Wartość zwracana

Przekształcona data i godzina.

## TimeZoneInfo::ConvertTime(DateTime, const TimeZoneInfoPtr\&) metoda

[Convert](../../convert/) czas do czasu w określonej strefie czasowej.

```cpp
static DateTime System::TimeZoneInfo::ConvertTime(DateTime date_time, const TimeZoneInfoPtr &destination_time_zone)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data i godzina do konwersji. |
| destination_time_zone | const [TimeZoneInfoPtr](../../timezoneinfoptr/)\& | Docelowa strefa czasowa. |

### Wartość zwracana

Przekształcona data i godzina.

## Zobacz też

* Typedef [TimeZoneInfoPtr](../../timezoneinfoptr/)
* Klasa [DateTime](../../datetime/)
* Klasa [TimeZoneInfo](../)
* Klasa [DateTimeOffset](../../datetimeoffset/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)