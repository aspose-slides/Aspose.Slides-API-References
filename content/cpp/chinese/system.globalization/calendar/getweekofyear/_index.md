---
title: GetWeekOfYear()
second_title: Aspose.Slides for C++ API 参考
description: 获取指定时间点所在的年份周数。
type: docs
weight: 352
url: /zh/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const 方法

获取指定时间点所在的年份周数。

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | 要提取数据的时间和日期。 |
| rule | [CalendarWeekRule](../../calendarweekrule/) | 确定一年中第一周的规则。 |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | 确定一周的第一天。 |

### 返回值

传入时间点的年份周号。

## 另见

* 枚举 [CalendarWeekRule](../../calendarweekrule/)
* 枚举 [DayOfWeek](../../../system/dayofweek/)
* 类 [DateTime](../../../system/datetime/)
* 类 [Calendar](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)