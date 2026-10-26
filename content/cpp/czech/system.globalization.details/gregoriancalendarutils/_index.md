---
title: GregorianCalendarUtils
second_title: Aspose.Slides pro C++ API Reference
description: Utility funkce gregoriánského kalendáře.
type: docs
weight: 1
url: /cs/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils třída


Gregorian calendar utility functions.

```cpp
class GregorianCalendarUtils
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) na ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate na [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Vytvoří gregoriánský ICU kalendář. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Získá vláknově lokální gregoriánský ICU kalendář. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Získá počet dnů ve specifickém měsíci. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Získá počet dnů ve specifickém roce. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Kontroluje, zda je den přestupný. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Kontroluje, zda je rok přestupný. |
## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maximální podporovaný gregoriánský rok. |
| static constexpr [MinYear](./minyear/) | Minimální podporovaný gregoriánský rok. |
## Viz také

* Jmenný prostor [System::Globalization::Details](../)
* Knihovna [Aspose.Slides](../../)