---
title: GregorianCalendarUtils
second_title: Aspose.Slides для C++ справочник API
description: Утилитные функции григорианского календаря.
type: docs
weight: 1
url: /ru/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils класс

Gregorian calendar utility functions.

```cpp
class GregorianCalendarUtils
```

## Методы

| Method | Описание |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) в ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate в [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Создать григорианский ICU календарь. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Получает локальный для потока григорианский ICU календарь. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Получает количество дней в указанном месяце. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Получает количество дней в указанном году. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Проверяет, является ли день високосным. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Проверяет, является ли год високосным. |

## Поля

| Field | Описание |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Максимальный поддерживаемый григорианский год. |
| static constexpr [MinYear](./minyear/) | Минимальный поддерживаемый григорианский год. |

## См. также

* Пространство имен [System::Globalization::Details](../)
* Библиотека [Aspose.Slides](../../)