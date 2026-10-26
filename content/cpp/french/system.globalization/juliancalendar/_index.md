---
title: JulianCalendar
second_title: Référence de l'API Aspose.Slides pour C++
description: "Calendrier julien. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défaillances d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 209
url: /fr/system.globalization/juliancalendar/
---
## JulianCalendar classe


Julian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JulianCalendar : public System::Globalization::Calendar
```

## Methods

| Méthode | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Ajoute des jours au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Ajoute des heures au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Ajoute des millisecondes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Ajoute des minutes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Ajoute des mois au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Ajoute des secondes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Ajoute des semaines au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Ajoute des années au point temporel. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Information RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crée une copie de l'objet actuel et renvoie un pointeur partagé vers celui-ci. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison en virgule flottante de style C# où deux NaN sont consideres comme egaux meme si selon IEC 60559:1989 le NaN n'est egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison en virgule flottante de style C# où deux NaN sont consideres comme egaux meme si selon IEC 60559:1989 le NaN n'est egal a aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour usage interne uniquement. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Obtient le type d'algorithme. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Obtient l'indice de l'ere actuelle. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Obtient la valeur de l'ere actuelle. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Obtient la liste des eras existant dans le calendrier. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Verifie si le calendrier est en lecture seule. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Point temporel maximal pris en charge par le calendrier. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Point temporel minimal pris en charge par le calendrier. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Obtient la derniere annee qui peut etre representee avec deux chiffres. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Obtient le jour du mois pour le point temporel specifie. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Obtient le jour de la semaine pour le point temporel specifie. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Obtient le jour de l'annee pour le point temporel specifie. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtient le nombre de jours dans le mois specifie. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtient le nombre de jours dans le mois specifie. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtient le nombre de jours dans le mois specifie. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Obtient le nombre de jours dans l'annee specifiee. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtient le nombre de jours dans l'annee specifiee. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtient le nombre de jours dans l'annee specifiee. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Obtient l'ere pour le point temporel specifie. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Obtient les heures pour le point temporel specifie. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtient le mois intercalair pour l'annee specifiee. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtient le mois intercalair pour l'annee specifiee. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtient le mois intercalair pour l'annee specifiee. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtient les millisecondes pour le point temporel specifie. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Obtient les minutes pour le point temporel specifie. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Obtient le mois pour le point temporel specifie. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtient le nombre de mois dans l'annee specifiee. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Information RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Information RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Obtient les secondes pour le point temporel specifie. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtient la semaine de l'annee pour le point temporel specifie. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Obtient l'annee pour le point temporel specifie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet représente une instance du type décrit par targetType. Analogue de l'operateur C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Verifie si le jour est bissextile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Verifie si le jour est bissextile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Verifie si le jour est bissextile. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Verifie si le mois est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Verifie si le mois est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Verifie si le mois est bissextile. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Verifie si l'annee est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Verifie si l'annee est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Verifie si l'annee est bissextile. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Verifie les valeurs d'annee, de mois, de jour et d'ere. |
|  [JulianCalendar](./juliancalendar/)() | Constructeur. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtient la version en lecture seule du calendrier. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees de la valeur specifiee. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Definie la derniere annee qui peut etre representee avec deux chiffres. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definie le n-ieme argument de modele comme pointeur faible (plutot que partage). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas être appele directement ; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas être appele directement ; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) a partir des composants. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) a partir des composants. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Convertit l'annee en annee a 4 chiffres en utilisant la propriete TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas être appele directement ; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas être appele directement ; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |
## Champs

| Champ | Description |
| --- | --- |
| static constexpr [JulianEra](./julianera/) | Ere julienne actuelle. |
## Voir aussi

* Classe [Calendar](../calendar/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)