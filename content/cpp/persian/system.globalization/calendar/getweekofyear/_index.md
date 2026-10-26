---
title: GetWeekOfYear()
second_title: Aspose.Slides برای مرجع API C++
description: هفتهٔ سال را برای نقطهٔ زمانی مشخص شده بر می‌گرداند.
type: docs
weight: 352
url: /fa/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const متد

هفتهٔ سال را برای نقطهٔ زمانی مشخص شده بر می‌گرداند.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | زمان و تاریخ برای استخراج داده‌ها. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | نحوه تعیین اولین هفتهٔ سال را مشخص می‌کند. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | اولین روز هفته را تعیین می‌کند. |

### مقدار بازگشتی

شمارهٔ هفتهٔ سال در نقطهٔ زمانی داده‌شده.

## موارد مرتبط

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [DateTime](../../../system/datetime/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)