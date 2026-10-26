---
title: GetWeekOfYear()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce la settimana dell'anno per il punto temporale specificato.
type: docs
weight: 352
url: /it/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const metodo

Restituisce la settimana dell'anno per il punto temporale specificato.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Data e ora da cui estrarre i dati. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Determina come stabilire la prima settimana dell'anno. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Determina il primo giorno della settimana. |

### Valore di ritorno

Numero della settimana dell'anno nel punto temporale fornito.

## Vedi anche

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Classe [DateTime](../../../system/datetime/)
* Classe [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)