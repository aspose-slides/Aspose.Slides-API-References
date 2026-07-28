---
title: GetWeekOfYear()
second_title: Aspose.Slides C++ API referencia
description: Lekéri az év hét számát a megadott időpontra.
type: docs
weight: 352
url: /hu/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const metódus

Visszaadja az év hét számát a megadott időpontra.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Az időpont és dátum, amelyből az adatokat ki kell nyerni. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Megadja, hogyan kell meghatározni az év első hetét. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Meghatározza a hét első napját. |

### Visszatérési érték

Az év hétszáma a megadott időpontban.

## Lásd még

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Osztály [DateTime](../../../system/datetime/)
* Osztály [Calendar](../)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)