---
title: GregorianCalendarUtils
second_title: مرجع API Aspose.Slides للغة C++
description: دوال مساعدة للتقويم الجريغوري.
type: docs
weight: 1
url: /ar/system.globalization.details/gregoriancalendarutils/
---
## فئة GregorianCalendarUtils

دوال مساعدة للتقويم الجريغوري.

```cpp
class GregorianCalendarUtils
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) إلى ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate إلى [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | إنشاء تقويم جريغوريان ICU. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | يحصل على تقويم جريغوريان ICU المحلي للثريد. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | يحصل على عدد الأيام في شهر محدد. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | يحصل على عدد الأيام في سنة محددة. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | يتحقق مما إذا كان اليوم كبيسًا. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | يتحقق مما إذا كانت السنة كبيسة. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | أكبر سنة جريغوريان مدعومة. |
| static constexpr [MinYear](./minyear/) | أصغر سنة جريغوريان مدعومة. |

## انظر أيضاً

* مساحة الاسم [System::Globalization::Details](../)
* المكتبة [Aspose.Slides](../../)