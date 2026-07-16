---
title: DateTimeFormatInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: "Ensemble de paramètres de formatage de date et d'heure. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou à l'aide de l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 66
url: /fr/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo classe

Ensemble de paramètres de formatage de date et d'heure. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou à l'aide de l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clone les informations de format. |
|  [DateTimeFormatInfo](./datetimeformatinfo/)() | Constructeur par défaut, construit des informations de format invariantes. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Obtient les noms de jour abrégés. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Obtient les noms de mois abrégés au génitif. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Obtient les noms de mois abrégés. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | Obtient le désignateur AM. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | Obtient le calendrier associé au formateur. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | Obtient la règle de semaine du calendrier associée au formateur. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Obtient le formateur de date et d'heure du thread actuel. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | Obtient le séparateur de date. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | Obtient les noms de jour. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Obtient le premier jour de la semaine. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Obtient le modèle complet de date et d'heure. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Obtient le formateur de date et d'heure invariant. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Vérifie si le formateur est en lecture seule. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | Obtient le modèle de date longue. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | Obtient le modèle d'heure longue. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | Obtient le modèle jour-mois. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Obtient les noms de mois au génitif. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | Obtient les noms de mois. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | Obtient le nom natif du calendrier si disponible. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | Obtient le désignateur PM. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Obtient le modèle RFC1123. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | Obtient le modèle de date courte. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | Obtient les noms de jour les plus courts possibles. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | Obtient le modèle d'heure courte. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Obtient le modèle de date et d'heure triable. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | Obtient le séparateur d'heure. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Obtient le modèle universel de date et d'heure triable. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | Obtient le modèle année-mois. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | Obtient le nom de jour de semaine abrégé. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Obtient le nom d'ère abrégé. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Obtient le nom de mois abrégé. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Obtient tous les modèles dans lesquels les valeurs de date et d'heure peuvent être formatées. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Obtient tous les modèles dans lesquels les valeurs de date et d'heure peuvent être formatées en utilisant la chaîne de format spécifiée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | Obtient le nom du jour de semaine. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | Obtient l'ère par son nom. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | Obtient le nom de l'ère. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Obtient le formateur d'un type spécifique. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Obtient le formateur associé au fournisseur de format. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Obtient le nom du mois d'année bissextile. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Obtient le nom du mois au génitif. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | Obtient le nom du mois. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | Obtient le nom le plus court pour le jour de semaine spécifié. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | Obtient la version en lecture seule du formateur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre indiqué. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de jour abrégés. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de mois abrégés au génitif. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de mois abrégés. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | Définit le désignateur AM. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | Définit le calendrier associé au formateur. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | Définit la règle de semaine du calendrier associée au formateur. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | Définit le séparateur de date. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de jour. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | Définit le premier jour de la semaine. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | Définit le modèle complet de date et d'heure. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | Définit le modèle de date longue. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | Définit le modèle d'heure longue. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | Définit le modèle jour-mois. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de mois au génitif. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de mois. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | Définit le désignateur PM. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | Définit le modèle de date courte. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les noms de jour les plus courts possibles. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | Définit le modèle d'heure courte. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | Définit le séparateur d'heure. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | Définit le modèle année-mois. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | Définit les modèles pour le format spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n'th argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir également

* Classe [Object](../../system/object/)
* Classe [IFormatProvider](../../system/iformatprovider/)
* Classe [ICloneable](../../system/icloneable/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)