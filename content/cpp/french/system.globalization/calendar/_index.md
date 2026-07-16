---
title: Calendar
second_title: Référence API Aspose.Slides pour C++
description: "Calendar qui définit comment les dates sont gérées, calculées, formatées, etc. Les operations de definition ne sont actives que sur des objets non en lecture seule. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() fonction. Ne jamais créer d'instance de ce type sur la pile ou avec l'operateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 1
url: /fr/system.globalization/calendar/
---
## Classe Calendar

[Calendar](./) qui définit comment les dates sont gérées, calculées, formatées, etc. Les opérations de définition ne sont activées que sur des objets non en lecture seule. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class Calendar : public System::ICloneable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Ajoute des jours au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Ajoute des heures au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Ajoute des millisecondes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Ajoute des minutes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Ajoute des mois au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Ajoute des secondes au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Ajoute des semaines au point temporel. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Ajoute des années au point temporel. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | Informations RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Crée une copie de l'objet actuel et renvoie un pointeur partagé vers celui-ci. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Obtient le type d'algorithme. |
| int [get_CurrentEra](./get_currentera/)() const | Obtient l'index de l'ère actuelle. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Obtient la valeur de l'ère actuelle. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Obtient la liste des ères existantes dans le calendrier. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Obtient l'identifiant du calendrier. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Vérifie si le calendrier est en lecture seule. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Point temporel maximal supporté par le calendrier. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Point temporel minimal supporté par le calendrier. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Obtient la dernière année pouvant être représentée par un format à deux chiffres. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Obtient le jour du mois pour le point temporel spécifié. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Obtient le jour de la semaine pour le point temporel spécifié. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Obtient le jour de l'année pour le point temporel spécifié. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Obtient le nombre de jours dans le mois spécifié. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Obtient le nombre de jours dans le mois spécifié. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Obtient le nombre de jours dans l'année spécifiée. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Obtient le nombre de jours dans l'année spécifiée. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Obtient l'ère pour le point temporel spécifié. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Obtient les heures pour le point temporel spécifié. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Obtient le mois intercalaire pour l'année spécifiée. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Obtient le mois intercalaire pour l'année spécifiée. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Obtient les millisecondes pour le point temporel spécifié. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Obtient les minutes pour le point temporel spécifié. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Obtient le mois pour le point temporel spécifié. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Obtient le nombre de mois dans l'année spécifiée. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Obtient le nombre de mois dans l'année spécifiée. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Obtient les secondes pour le point temporel spécifié. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Obtient la semaine de l'année pour le point temporel spécifié. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Obtient l'année pour le point temporel spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Vérifie si le jour est bissextile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Vérifie si le jour est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Vérifie si le mois est bissextile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Vérifie si le mois est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Vérifie si l'année est bissextile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Vérifie si l'année est bissextile. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Vérifie les valeurs d'année, de mois, de jour et d'ère. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Obtient la version en lecture seule du calendrier. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Définit la dernière année pouvant être représentée par un format à deux chiffres. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) à partir des composants. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construit l'objet [DateTime](../../system/datetime/) à partir des composants. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Convertit l'année en année à 4 chiffres en utilisant la propriété TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [ICloneable](../../system/icloneable/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)