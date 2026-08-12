---
title: GetWeekOfYear()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับสัปดาห์ของปีสำหรับจุดเวลาที่ระบุ
type: docs
weight: 352
url: /th/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const เมธอด

รับหมายเลขสัปดาห์ของปีสำหรับจุดเวลาที่กำหนด

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | เวลาและวันที่ที่จะดึงข้อมูลจาก |
| rule | [CalendarWeekRule](../../calendarweekrule/) | กำหนดวิธีการหาสัปดาห์แรกของปี |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | กำหนดวันแรกของสัปดาห์ |

### ค่าที่คืน

หมายเลขสัปดาห์ของปีในจุดเวลาที่ส่ง

## ดูเพิ่มเติม

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Class [DateTime](../../../system/datetime/)
* Class [Calendar](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)