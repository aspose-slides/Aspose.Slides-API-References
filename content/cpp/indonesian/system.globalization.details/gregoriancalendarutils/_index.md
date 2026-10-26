---
title: GregorianCalendarUtils
second_title: Aspose.Slides untuk Referensi API C++
description: Fungsi utilitas kalender Gregorian.
type: docs
weight: 1
url: /id/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils kelas

Fungsi utilitas kalender Gregorian.

```cpp
class GregorianCalendarUtils
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) menjadi ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate menjadi [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Buat kalender ICU Gregorian. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Mendapatkan kalender ICU Gregorian thread-local. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Mendapatkan jumlah hari dalam bulan tertentu. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Mendapatkan jumlah hari dalam tahun tertentu. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Memeriksa apakah hari tersebut kabisat. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Memeriksa apakah tahun tersebut kabisat. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Tahun Gregorian maksimum yang didukung. |
| static constexpr [MinYear](./minyear/) | Tahun Gregorian minimum yang didukung. |
## Lihat Juga

* Ruang Nama [System::Globalization::Details](../)
* Perpustakaan [Aspose.Slides](../../)