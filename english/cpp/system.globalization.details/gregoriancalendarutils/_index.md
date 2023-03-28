---
title: GregorianCalendarUtils
second_title: Aspose.Slides for C++ API Reference
description: Gregorian calendar utility functions.
type: docs
weight: 1
url: /cpp/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils class


Gregorian calendar utility functions.

```cpp
class GregorianCalendarUtils
```

## Methods

| Method | Description |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) to ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate to [DateTime](../../system/datetime/). |
| static std::unique_ptr\<icu::Calendar\> [CreateCalendar](./createcalendar/)() | Create gregorian ICU calendar. |
| static icu::Calendar\& [GetCalendar](./getcalendar/)() | Gets thread-local gregorian ICU calendar. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Gets number of days in specific month. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Gets number of days in specific year. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Checks if the day is leap. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Checks if the year is leap. |
## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Max supported Gregorian year. |
| static constexpr [MinYear](./minyear/) | Min supported Gregorian year. |
## See Also

* Namespace [System::Globalization::Details](../)
* Library [Aspose.Slides](../../)
