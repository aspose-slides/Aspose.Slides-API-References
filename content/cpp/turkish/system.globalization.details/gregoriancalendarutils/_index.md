---
title: GregorianCalendarUtils
second_title: Aspose.Slides için C++ API Referansı
description: Gregoryen takvim yardımcı fonksiyonları.
type: docs
weight: 1
url: /tr/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils sınıfı

Gregoryen takvim yardımcı fonksiyonları.

```cpp
class GregorianCalendarUtils
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) ICU UDate'ye. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate'yi [DateTime](../../system/datetime/)'ye. |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Gregoryen ICU takvim oluşturur. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | İş parçacığı yerel Gregoryen ICU takvimini alır. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Belirli ayın gün sayısını alır. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Belirli yılın gün sayısını alır. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Günün artık yıl olup olmadığını denetler. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Yılın artık yıl olup olmadığını denetler. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Desteklenen maksimum Gregoryen yıl. |
| static constexpr [MinYear](./minyear/) | Desteklenen minimum Gregoryen yıl. |

## Ayrıca Bakınız

* Ad alanı [System::Globalization::Details](../)
* Kütüphane [Aspose.Slides](../../)