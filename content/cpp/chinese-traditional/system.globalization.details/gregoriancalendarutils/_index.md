---
title: GregorianCalendarUtils
second_title: Aspose.Slides for C++ API 參考
description: 格里曆工具函式。
type: docs
weight: 1
url: /zh-hant/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils 類別

格里曆工具函式。

```cpp
class GregorianCalendarUtils
```

## 方法

| Method | Description |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) to ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate to [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | 建立公曆 ICU 行事曆。 |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | 取得執行緒本機公曆 ICU 行事曆。 |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | 取得特定月份的天數。 |
| static int [GetDaysInYear](./getdaysinyear/)(int) | 取得特定年份的天數。 |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | 檢查此日是否為閏日。 |
| static **bool** [IsLeapYear](./isleapyear/)(int) | 檢查此年是否為閏年。 |

## 欄位

| Field | Description |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | 支援的最大 Gregorian 年份。 |
| static constexpr [MinYear](./minyear/) | 支援的最小 Gregorian 年份。 |

## 相關參考

* Namespace [System::Globalization::Details](../)
* Library [Aspose.Slides](../../)