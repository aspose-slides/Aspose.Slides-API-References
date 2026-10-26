---
title: GregorianCalendarUtils
second_title: Riferimento API di Aspose.Slides per C++
description: Funzioni di utilità del calendario gregoriano.
type: docs
weight: 1
url: /it/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils classe


Funzioni di utilità del calendario gregoriano.

```cpp
class GregorianCalendarUtils
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) a ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate a [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Crea calendario ICU gregoriano. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Ottiene il calendario ICU gregoriano locale al thread. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Restituisce il numero di giorni nel mese specificato. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Restituisce il numero di giorni nell'anno specificato. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Verifica se il giorno è bisestile. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Verifica se l'anno è bisestile. |
## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Anno gregoriano massimo supportato. |
| static constexpr [MinYear](./minyear/) | Anno gregoriano minimo supportato. |
## Vedi anche

* Namespace [System::Globalization::Details](../)
* Library [Aspose.Slides](../../)