---
title: GregorianCalendarUtils
second_title: Referência da API Aspose.Slides para C++
description: Funções utilitárias do calendário gregoriano.
type: docs
weight: 1
url: /pt/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils classe


Funções utilitárias do calendário gregoriano.

```cpp
class GregorianCalendarUtils
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) para ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate para [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Cria calendário gregoriano ICU. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Obtém calendário gregoriano ICU local da thread. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Obtém o número de dias no mês específico. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Obtém o número de dias no ano específico. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Verifica se o dia é bissexto. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Verifica se o ano é bissexto. |
## Campos

| Campo | Descrição |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Ano gregoriano máximo suportado. |
| static constexpr [MinYear](./minyear/) | Ano gregoriano mínimo suportado. |
## Veja Também

* Namespace [System::Globalization::Details](../)
* Biblioteca [Aspose.Slides](../../)