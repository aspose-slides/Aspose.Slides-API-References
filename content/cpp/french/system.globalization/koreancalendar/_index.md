---
title: KoreanCalendar
second_title: Aspose.Slides pour C++ Référence d'API
description: "Calendrier coréen. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 222
url: /fr/system.globalization/koreancalendar/
---
## KoreanCalendar classe

Calendrier coréen. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## Méthodes

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
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informations RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crée une copie de l'objet actuel et renvoie un pointeur partagé vers celui-ci. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Obtient le type d'algorithme. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Obtient l'index de l'ère actuelle. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Obtient la valeur de l'ère actuelle. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Obtient la liste des ères existantes dans le calendrier. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Vérifie si le calendrier est en lecture seule. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Point temporel maximal supporté par le calendrier. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Point temporel minimal supporté par le calendrier. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Obtient la dernière année pouvant être représentée sur 2 chiffres. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Obtient le jour du mois pour le point temporel spécifié. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Obtient le jour de la semaine pour le point temporel spécifié. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Obtient le jour de l'année pour le point temporel spécifié. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Obtient le nombre de jours dans le mois spécifié. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtient le nombre de jours dans le mois spécifié. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtient le nombre de jours dans le mois spécifié. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Obtient le nombre de jours dans l'année spécifiée. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtient le nombre de jours dans l'année spécifiée. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtient le nombre de jours dans l'année spécifiée. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Obtient l'ère pour le point temporel spécifié. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Obtient les heures pour le point temporel spécifié. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Obtient le mois intercalaire pour l'année spécifiée. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtient le mois intercalaire pour l'année spécifiée. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtient le mois intercalaire pour l'année spécifiée. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtient les millisecondes pour le point temporel spécifié. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Obtient les minutes pour le point temporel spécifié. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Obtient le mois pour le point temporel spécifié. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Obtient le nombre de mois dans l'année spécifiée. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Informations RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Informations RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Obtient les secondes pour le point temporel spécifié. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtient la semaine de l'année pour le point temporel spécifié. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Obtient l'année pour le point temporel spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Vérifie si le jour est bissextile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Vérifie si le jour est bissextile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Vérifie si le jour est bissextile. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Vérifie si le mois est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Vérifie si le mois est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Vérifie si le mois est bissextile. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Vérifie si l'année est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Vérifie si l'année est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Vérifie si l'année est bissextile. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Vérifie les valeurs de l'année, du mois, du jour et de l'ère. |
|  [KoreanCalendar](./koreancalendar/)() | Constructeur. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction de copie des sous-classes. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction de copie des sous-classes. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtient la version en lecture seule du calendrier. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagé de la valeur spécifiée. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Définit la dernière année pouvant être représentée sur 2 chiffres. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Autorise le basculement des pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Construit l'objet [DateTime](../../system/datetime/) à partir des composants. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) à partir des composants. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) à partir des composants. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Convertit l'année en année à 4 chiffres en utilisant la propriété TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | Ère coréenne actuelle. |

## Voir aussi

* Classe [Calendar](../calendar/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)