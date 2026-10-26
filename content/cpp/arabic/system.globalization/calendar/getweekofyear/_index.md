---
title: GetWeekOfYear()
second_title: مرجع API Aspose.Slides للغة C++
description: يُرجع رقم الأسبوع من السنة للنقطة الزمنية المحددة.
type: docs
weight: 352
url: /ar/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const طريقة

يُرجع رقم الأسبوع من السنة للنقطة الزمنية المحددة.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | الوقت والتاريخ لاستخراج البيانات منه. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | يحدد كيفية تحديد الأسبوع الأول من السنة. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | يحدد أول يوم في الأسبوع. |

### قيمة الإرجاع

رقم أسبوع السنة في النقطة الزمنية المُمرَّرة.

## انظر أيضاً

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* فئة [DateTime](../../../system/datetime/)
* فئة [Calendar](../)
* مساحة الاسم [System::Globalization](../../)
* مكتبة [Aspose.Slides](../../../)