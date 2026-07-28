---
title: GregorianCalendarUtils
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Funkcje pomocnicze kalendarza gregoriańskiego.
type: docs
weight: 1
url: /pl/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils klasa

Funkcje pomocnicze kalendarza gregoriańskiego.

```cpp
class GregorianCalendarUtils
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) do ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate do [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Utwórz kalendarz gregoriański ICU. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Pobiera wątkowo-lokalny kalendarz gregoriański ICU. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Pobiera liczbę dni w określonym miesiącu. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Pobiera liczbę dni w określonym roku. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Sprawdza, czy dzień jest przestępny. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Sprawdza, czy rok jest przestępny. |

## Pola

| Pole | Opis |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Maksymalny obsługiwany rok gregoriański. |
| static constexpr [MinYear](./minyear/) | Minimalny obsługiwany rok gregoriański. |

## Zobacz także

* Przestrzeń nazw [System::Globalization::Details](../)
* Biblioteka [Aspose.Slides](../../)