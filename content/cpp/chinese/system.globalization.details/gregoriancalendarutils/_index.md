---
title: GregorianCalendarUtils
second_title: Aspose.Slides for C++ API 参考
description: 公历实用函数。
type: docs
weight: 1
url: /zh/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils 类

公历实用函数。

```cpp
class GregorianCalendarUtils
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) 到 ICU UDate。 |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate 到 [DateTime](../../system/datetime/)。 |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | 创建公历 ICU 日历。 |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | 获取线程本地公历 ICU 日历。 |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | 获取特定月份的天数。 |
| static int [GetDaysInYear](./getdaysinyear/)(int) | 获取特定年份的天数。 |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | 检查该天是否为闰日。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 检查该年是否为闰年。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | 支持的最大公历年份。 |
| static constexpr [MinYear](./minyear/) | 支持的最小公历年份。 |

## 另请参阅

* 命名空间 [System::Globalization::Details](../)
* 库 [Aspose.Slides](../../)