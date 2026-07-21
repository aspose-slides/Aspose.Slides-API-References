---
title: GetWeekOfYear()
second_title: Справочник API Aspose.Slides для C++
description: Получает номер недели года для указанного момента времени.
type: docs
weight: 352
url: /ru/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const метод


Получает номер недели в году для указанного момента времени.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Время и дата, из которых извлекаются данные. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Определяет, как установить первую неделю года. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Определяет первый день недели. |

### Возвращаемое значение

Номер недели года в указанном моменте времени.

## См. также

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Класс [DateTime](../../../system/datetime/)
* Класс [Calendar](../)
* Пространство имён [System::Globalization](../../)
* Library [Aspose.Slides](../../../)