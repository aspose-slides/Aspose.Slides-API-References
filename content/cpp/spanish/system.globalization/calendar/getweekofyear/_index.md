---
title: GetWeekOfYear()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la semana del año para el punto de tiempo especificado.
type: docs
weight: 352
url: /es/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const método


Obtiene la semana del año para el punto de tiempo especificado.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Hora y fecha de la que extraer datos. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Determina cómo determinar la primera semana del año. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Determina el primer día de la semana. |

### Valor devuelto

Número de semana del año en el punto de tiempo proporcionado.

## Ver también

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [DateTime](../../../system/datetime/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)