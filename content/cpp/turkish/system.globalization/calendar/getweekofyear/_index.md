---
title: GetWeekOfYear()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen zaman noktası için yılın haftasını alır.
type: docs
weight: 352
url: /tr/system.globalization/calendar/getweekofyear/
---
## Calendar::GetWeekOfYear(DateTime, CalendarWeekRule, DayOfWeek) const metod

Belirtilen zaman noktasının yıl içindeki haftasını alır.

```cpp
virtual int System::Globalization::Calendar::GetWeekOfYear(DateTime time, CalendarWeekRule rule, DayOfWeek first_day_of_week) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| time | [DateTime](../../../system/datetime/) | Verinin çıkarılacağı zaman ve tarih. |
| rule | [CalendarWeekRule](../../calendarweekrule/) | Yılın ilk haftasının nasıl belirleneceğini belirler. |
| first_day_of_week | [DayOfWeek](../../../system/dayofweek/) | Haftanın ilk gününü belirler. |

### Dönüş Değeri

Verilen zaman noktasındaki yılın hafta numarası.

## Ayrıca Bakınız

* Enum [CalendarWeekRule](../../calendarweekrule/)
* Enum [DayOfWeek](../../../system/dayofweek/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [Calendar](../)
* Ad Alanı [System::Globalization](../../)
* Library [Aspose.Slides](../../../)