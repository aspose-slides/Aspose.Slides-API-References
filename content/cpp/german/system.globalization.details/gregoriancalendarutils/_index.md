---
title: GregorianCalendarUtils
second_title: Aspose.Slides für C++ API-Referenz
description: Hilfsfunktionen für den Gregorianischen Kalender.
type: docs
weight: 1
url: /de/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils Klasse

Hilfsfunktionen für den Gregorianischen Kalender.

```cpp
class GregorianCalendarUtils
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) zu ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate zu [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Erstellt einen gregorianischen ICU-Kalender. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Ruft den thread-lokalen gregorianischen ICU-Kalender ab. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Ermittelt die Anzahl der Tage im angegebenen Monat. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Ermittelt die Anzahl der Tage im angegebenen Jahr. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Prüft, ob der Tag ein Schaltjahr ist. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Prüft, ob das Jahr ein Schaltjahr ist. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maximal unterstütztes Gregorianisches Jahr. |
| static constexpr [MinYear](./minyear/) | Minimal unterstütztes Gregorianisches Jahr. |

## Siehe auch

* Namensraum [System::Globalization::Details](../)
* Bibliothek [Aspose.Slides](../../)