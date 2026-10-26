---
title: GregorianCalendarUtils
second_title: Aspose.Slides برای C++ مرجع API
description: توابع ابزار تقویم گریگوری.
type: docs
weight: 1
url: /fa/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils کلاس

توابع ابزار تقویم گریگوری.

```cpp
class GregorianCalendarUtils
```

## متدها

| متد | توضیح |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) به ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate به [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | ایجاد تقویم ICU گریگوری. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | دریافت تقویم ICU گریگوری محلی-رشته. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | دریافت تعداد روزها در ماه مشخص. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | دریافت تعداد روزها در سال مشخص. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | بررسی می‌کند آیا روز کبیسه است. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | بررسی می‌کند آیا سال کبیسه است. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | حداکثر سال گریگوری پشتیبانی‌شده. |
| static constexpr [MinYear](./minyear/) | حداقل سال گریگوری پشتیبانی‌شده. |

## موارد مرتبط

* فضای‌نام [System::Globalization::Details](../)
* کتابخانه [Aspose.Slides](../../)