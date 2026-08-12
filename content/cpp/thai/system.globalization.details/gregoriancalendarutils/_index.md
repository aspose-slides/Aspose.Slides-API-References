---
title: GregorianCalendarUtils
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ฟังก์ชันยูทิลิตี้ของปฏิทินเกรกอเรียน
type: docs
weight: 1
url: /th/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils คลาส

Gregorian calendar utility functions.

```cpp
class GregorianCalendarUtils
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) เป็น ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate เป็น [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | สร้างปฏิทิน gregorian ICU. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | ดึงปฏิทิน gregorian ICU แบบ thread-local. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | ดึงจำนวนวันในเดือนที่ระบุ. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | ดึงจำนวนวันในปีที่ระบุ. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | ตรวจสอบว่าวันนั้นเป็นวันอธิกสุรทินหรือไม่. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | ตรวจสอบว่าปีเป็นปีอธิกสุรทินหรือไม่. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | ปี Gregorian สูงสุดที่รองรับ. |
| static constexpr [MinYear](./minyear/) | ปี Gregorian ต่ำสุดที่รองรับ. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Globalization::Details](../)
* ไลบรารี [Aspose.Slides](../../)