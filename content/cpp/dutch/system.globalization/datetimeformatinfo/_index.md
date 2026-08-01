---
title: DateTimeFormatInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Set van datum- en tijdopmaakparameters. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Omhul deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 66
url: /nl/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo klasse

Set van datum- en tijdopmaakparameters. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Omhul deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Kloont formatinfo. |
| [DateTimeFormatInfo](./datetimeformatinfo/)() | Standaardconstructor, maakt invariant formatinfo aan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetalvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetalvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Haalt verkorte dagnamen op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Haalt verkorte maandnamen in genitiefvorm op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Haalt verkorte maandnamen op. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | Haalt AM-aanduiding op. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | Haalt de kalender op die bij de formatter is gekoppeld. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | Haalt de kalenderweekregel op die bij de formatter is gekoppeld. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Haalt de datum- en tijd-formatter van de huidige thread op. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | Haalt datum-scheidingsteken op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | Haalt dagnamen op. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Haalt de eerste dag van de week op. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Haalt volledig datum- en tijdpatroon op. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Haalt invariant datum- en tijd-formatter op. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Controleert of de formatter alleen-lezen is. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | Haalt lang datum-patroon op. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | Haalt lang tijd-patroon op. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | Haalt maand-dag-patroon op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Haalt maandnamen in genitiefvorm op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | Haalt maandnamen op. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | Haalt de native kalendernaam op indien beschikbaar. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | Haalt PM-aanduiding op. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Haalt RFC1123-patroon op. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | Haalt kort datum-patroon op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | Haalt de kortst mogelijke dagnamen op. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | Haalt kort tijd-patroon op. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Haalt sorteerbaar datum- en tijd-patroon op. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | Haalt tijd-scheidingsteken op. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Haalt universeel sorteerbaar datum- en tijd-patroon op. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | Haalt jaar-en-maand-patroon op. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | Haalt verkorte weekdagnaam op. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Haalt verkorte era-naam op. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Haalt verkorte maandnaam op. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Haalt alle patronen op waarin datum- en tijdwaarden kunnen worden opgemaakt. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Haalt alle patronen op waarin datum- en tijdwaarden kunnen worden opgemaakt met de opgegeven opmaak-string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | Haalt weekdagnaam op. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | Haalt era op op naam. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | Haalt eranaam op. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Haalt formatter van specifiek type op. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Haalt formatter op die bij de format-provider hoort. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Haalt schrikkelmaand-naam op. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Haalt genitieve maandnaam op. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | Haalt maandnaam op. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | Haalt de kortste naam voor de opgegeven weekdag op. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# ‘is’-operator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | Haalt alleen-lees versie van de formatter op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt verkorte dagnamen in. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt verkorte maandnamen in genitiefvorm in. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt verkorte maandnamen in. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | Stelt AM-aanduiding in. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | Stelt de kalender in die bij de formatter hoort. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | Stelt de kalenderweekregel in die bij de formatter hoort. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | Stelt datum-scheidingsteken in. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt dagnamen in. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | Stelt de eerste dag van de week in. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | Stelt volledig datum- en tijd-patroon in. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | Stelt lang datum-patroon in. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | Stelt lang tijd-patroon in. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | Stelt maand-dag-patroon in. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt maandnamen in genitiefvorm in. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt maandnamen in. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | Stelt PM-aanduiding in. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | Stelt kort datum-patroon in. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Stelt de kortst mogelijke dagnamen in. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | Stelt kort tijd-patroon in. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | Stelt tijd-scheidingsteken in. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | Stelt jaar-en-maand-patroon in. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | Stelt patronen in voor de gespecificeerde opmaak. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een zwakke pointer (in plaats van een gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaker-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Klasse [IFormatProvider](../../system/iformatprovider/)
* Klasse [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)