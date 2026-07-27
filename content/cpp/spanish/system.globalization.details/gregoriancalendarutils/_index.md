---
title: GregorianCalendarUtils
second_title: Referencia de API de Aspose.Slides para C++
description: Funciones de utilidad del calendario gregoriano.
type: docs
weight: 1
url: /es/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils clase


Funciones de utilidad del calendario gregoriano.

```cpp
class GregorianCalendarUtils
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) a ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate a [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Crear calendario gregoriano ICU. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Obtiene el calendario gregoriano ICU local al hilo. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Obtiene el número de días en el mes específico. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Obtiene el número de días en el año específico. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Comprueba si el día es bisiesto. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Comprueba si el año es bisiesto. |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Año gregoriano máximo admitido. |
| static constexpr [MinYear](./minyear/) | Año gregoriano mínimo admitido. |

## Ver también

* Espacio de nombres [System::Globalization::Details](../)
* Biblioteca [Aspose.Slides](../../)