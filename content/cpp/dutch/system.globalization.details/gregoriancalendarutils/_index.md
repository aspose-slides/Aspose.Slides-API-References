---
title: GregorianCalendarUtils
second_title: Aspose.Slides voor C++ API-referentie
description: Hulpfuncties voor de gregoriaanse kalender.
type: docs
weight: 1
url: /nl/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils klasse

Hulpfuncties voor de gregoriaanse kalender.

```cpp
class GregorianCalendarUtils
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) naar ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate naar [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Maak gregoriaanse ICU kalender. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Haalt thread-lokale gregoriaanse ICU kalender op. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Haalt aantal dagen in een specifieke maand op. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Haalt aantal dagen in een specifiek jaar op. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Controleert of de dag een schrikkeldag is. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Controleert of het jaar een schrikkeljaar is. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maximaal ondersteund gregoriaans jaar. |
| static constexpr [MinYear](./minyear/) | Minimaal ondersteund gregoriaans jaar. |

## Zie ook

* Naamruimte [System::Globalization::Details](../)
* Bibliotheek [Aspose.Slides](../../)