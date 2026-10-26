---
title: GetWeekOfYear()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定時間點的年度週次。
type: docs
weight: 352
url: /zh-hant/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const 方法

取得指定時間點的年度週次。

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | 要從中擷取資料的時間和日期。 |
| rule | [CalendarWeekRule](../../calendarweekrule/) | 決定如何確定該年的第一週。 |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | 決定一週的第一天。 |

### 傳回值

傳入時間點的年份週號。

## 參見

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* 類別 [DateTime](../../../system/datetime/)
* 類別 [Calendar](../)
* 命名空間 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)