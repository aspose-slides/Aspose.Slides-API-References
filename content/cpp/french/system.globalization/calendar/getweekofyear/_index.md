---
title: GetWeekOfYear()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la semaine de l'année pour le point temporel spécifié.
type: docs
weight: 352
url: /fr/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const method

Obtient la semaine de l'année pour le point temporel spécifié.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Heure et date dont extraire les données. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Détermine comment déterminer la première semaine de l'année. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Détermine le premier jour de la semaine. |

### Valeur retournée

Numéro de semaine de l'année pour le point temporel fourni.

## Voir aussi

* Enumération [CalendarWeekRule](../../calendarweekrule/)
* Enumération [DayOfWeek](../../../system/dayofweek/)
* Classe [DateTime](../../../system/datetime/)
* Classe [Calendar](../)
* Espace de noms [System::Globalization](../../)
* Bibliothèque [Aspose.Slides](../../../)