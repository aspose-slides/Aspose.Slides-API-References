---
title: GetWeekOfYear()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Woche des Jahres für den angegebenen Zeitpunkt.
type: docs
weight: 352
url: /de/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const Methode

Ermittelt die Woche des Jahres für den angegebenen Zeitpunkt.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Zeit und Datum, aus denen Daten extrahiert werden. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Bestimmt, wie die erste Woche des Jahres ermittelt wird. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Bestimmt den ersten Wochentag. |

### Rückgabewert

Jahreswochenzahl im übergebenen Zeitpunkt.

## Siehe auch

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Klasse [DateTime](../../../system/datetime/)
* Klasse [Calendar](../)
* Namensraum [System::Globalization](../../)
* Bibliothek [Aspose.Slides](../../../)