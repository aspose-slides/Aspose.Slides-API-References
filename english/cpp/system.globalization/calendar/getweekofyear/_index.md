---
title: GetWeekOfYear()
second_title: Aspose.Slides for C++ API Reference
description: Gets week of the year for the specified time point.
type: docs
weight: 352
url: /cpp/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const method


Gets week of the year for the specified time point.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Time and date to extract data from. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Determines how to determine the first week of the year. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Determines first day of week. |

### Return Value

Year week number in the time point passed.

## See Also

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [DateTime](../../../system/datetime/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)