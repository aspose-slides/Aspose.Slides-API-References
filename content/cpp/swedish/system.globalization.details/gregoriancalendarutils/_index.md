---
title: GregorianCalendarUtils
second_title: Aspose.Slides för C++ API-referens
description: Verktygsfunktioner för den gregorianska kalendern.
type: docs
weight: 1
url: /sv/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils klass


Gregorian kalender verktygsfunktioner.

```cpp
class GregorianCalendarUtils
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) till ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate till [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Skapa gregoriansk ICU-kalender. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Hämtar trådlokal gregoriansk ICU-kalender. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Hämtar antalet dagar i en specifik månad. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Hämtar antalet dagar i ett specifikt år. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Kontrollerar om dagen är skottår. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Kontrollerar om året är skottår. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maximalt stöttade gregorianska år. |
| static constexpr [MinYear](./minyear/) | Minimalt stöttade gregorianska år. |
## Se även

* Namnrymd [System::Globalization::Details](../)
* Bibliotek [Aspose.Slides](../../)