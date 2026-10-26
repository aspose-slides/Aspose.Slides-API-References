---
title: GregorianCalendarUtils
second_title: Aspose.Slides για C++ Αναφορά API
description: Λειτουργίες βοηθητικού προγράμματος ημερολογίου Γρηγοριανού.
type: docs
weight: 1
url: /el/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils κλάση

Λειτουργίες βοηθητικού προγράμματος ημερολογίου Γρηγοριανού.

```cpp
class GregorianCalendarUtils
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) σε ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate σε [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Δημιουργεί ημερολόγιο ICU Γρηγοριανό. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Αποκτά το τοπικό του νήματος ημερολόγιο ICU Γρηγοριανό. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Λαμβάνει αριθμό ημερών σε συγκεκριμένο μήνα. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Λαμβάνει αριθμό ημερών σε συγκεκριμένο έτος. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Ελέγχει αν το έτος είναι δίσεκτο. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Μέγιστο υποστηριζόμενο έτος Γρηγοριανού. |
| static constexpr [MinYear](./minyear/) | Ελάχιστο υποστηριζόμενο έτος Γρηγοριανού. |
## Δείτε επίσης

* Χώρος ονομάτων [System::Globalization::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)