---
title: GetWeekOfYear()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar veckonummer för året för den angivna tidpunkten.
type: docs
weight: 352
url: /sv/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const metod


Hämtar veckonummer för året för den angivna tidpunkten.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Tid och datum att extrahera data från. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Bestämmer hur den första veckan på året ska fastställas. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Bestämmer veckans första dag. |

### Returvärde

Veckonummer för året i den angivna tidpunkten.

## Se även

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Klass [DateTime](../../../system/datetime/)
* Klass [Calendar](../)
* Namnrymd [System::Globalization](../../)
* Library [Aspose.Slides](../../../)