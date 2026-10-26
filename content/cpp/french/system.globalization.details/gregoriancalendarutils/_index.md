---
title: GregorianCalendarUtils
second_title: Référence API Aspose.Slides pour C++
description: Fonctions utilitaires du calendrier grégorien.
type: docs
weight: 1
url: /fr/system.globalization.details/gregoriancalendarutils/
---
## GregorianCalendarUtils classe

Fonctions utilitaires du calendrier grégorien.

```cpp
class GregorianCalendarUtils
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **double** [ConvertDateTimeToUDate](./convertdatetimetoudate/)([DateTime](../../system/datetime/)) | [Convert](../../system/convert/)[DateTime](../../system/datetime/) vers ICU UDate. |
| static [DateTime](../../system/datetime/) [ConvertUDateToDateTime](./convertudatetodatetime/)(const **double**) | [Convert](../../system/convert/) ICU UDate vers [DateTime](../../system/datetime/). |
| static std::unique_ptr\<codeporting_icu::Calendar\> [CreateCalendar](./createcalendar/)() | Créer un calendrier ICU grégorien. |
| static codeporting_icu::Calendar\& [GetCalendar](./getcalendar/)() | Obtient le calendrier ICU grégorien local au thread. |
| static int [GetDaysInMonth](./getdaysinmonth/)(int, int) | Obtient le nombre de jours du mois spécifique. |
| static int [GetDaysInYear](./getdaysinyear/)(int) | Obtient le nombre de jours de l'année spécifique. |
| static **bool** [IsLeapDay](./isleapday/)(int, int, int) | Vérifie si le jour est bissextile. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Vérifie si l'année est bissextile. |
## Champs

| Champ | Description |
| --- | --- |
| static constexpr [MaxYear](./maxyear/) | Année grégorienne maximale prise en charge. |
| static constexpr [MinYear](./minyear/) | Année grégorienne minimale prise en charge. |
## Voir aussi

* Espace de noms [System::Globalization::Details](../)
* Bibliothèque [Aspose.Slides](../../)