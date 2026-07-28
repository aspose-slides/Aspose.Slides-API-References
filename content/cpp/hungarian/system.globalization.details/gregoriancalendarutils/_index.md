---
title: GregorianCalendarUtils
second_title: Aspose.Slides C++ API Referenciája
description: Gregorian naptár segédfüggvényei.
type: docs
weight: 1
url: /hu/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils osztály


Gregorian naptár segédfüggvényei.

```cpp
class GregorianCalendarUtils
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) az ICU UDate-re. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate-t [DateTime](../../system/datetime/)-re. |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Gregorian ICU naptár létrehozása. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Lekéri a szálonként lokális gregorian ICU naptárat. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Visszaadja a napok számát egy adott hónapban. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Visszaadja a napok számát egy adott évben. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Ellenőrzi, hogy a nap szökőnap-e. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Ellenőrzi, hogy az év szökőév-e. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maximálisan támogatott gregoriánus év. |
| static constexpr [MinYear](./minyear/) | Minimálisan támogatott gregoriánus év. |

## Lásd még

* Névtér [System::Globalization::Details](../)
* Könyvtár [Aspose.Slides](../../)