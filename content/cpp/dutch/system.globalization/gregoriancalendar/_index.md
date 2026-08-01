---
title: GregorianCalendar
second_title: Aspose.Slides voor C++ API-referentie
description: "Gregoriaanse kalender. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om het als argument aan functies door te geven."
type: docs
weight: 131
url: /nl/system.globalization/gregoriancalendar/
---
## GregorianCalendar klasse

Gregoriaanse kalender. Objecten van deze klasse moeten alleen worden toegewezen met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om het als argument aan functies door te geven.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Voegt dagen toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Voegt uren toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Voegt milliseconden toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Voegt minuten toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Voegt maanden toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Voegt seconden toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Voegt weken toe aan tijdstip. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Voegt jaren toe aan tijdstip. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-informatie. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Maakt een kopie van het huidige object en retourneert een shared pointer ernaar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Haalt algoritmetype op. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | Haalt Gregoriaans kalendertype op. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Haalt index van huidige era op. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Haalt waarde van huidige era op. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Haalt lijst van eras die in de kalender bestaan op. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Controleert of de kalender alleen-lezen is. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximum tijdstip dat door de kalender wordt ondersteund. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimum tijdstip dat door de kalender wordt ondersteund. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Haalt het laatste jaar op dat kan worden weergegeven met twee cijfers. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die bij het object hoort. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Haalt dag van de maand op voor het opgegeven tijdstip. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Haalt dag van de week op voor het opgegeven tijdstip. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Haalt dag van het jaar op voor het opgegeven tijdstip. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Haalt aantal dagen in een specifieke maand op. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Haalt aantal dagen in een specifieke maand op. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Haalt aantal dagen in een specifieke maand op. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Haalt aantal dagen in een specifiek jaar op. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Haalt aantal dagen in een specifiek jaar op. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Haalt aantal dagen in een specifiek jaar op. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | Haalt standaard gregoriaanse kalenderinstantie op. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Haalt era op voor het opgegeven tijdstip. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Haalt uren op voor het opgegeven tijdstip. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Haalt de schrikkelmaand op voor het opgegeven jaar. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Haalt de schrikkelmaand op voor het opgegeven jaar. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Haalt de schrikkelmaand op voor het opgegeven jaar. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Haalt milliseconden op voor het opgegeven tijdstip. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Haalt minuten op voor het opgegeven tijdstip. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Haalt maand op voor het opgegeven tijdstip. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Haalt aantal maanden op in het opgegeven jaar. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-informatie. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-informatie. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Haalt seconden op voor het opgegeven tijdstip. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt daadwerkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Haalt week van het jaar op voor het opgegeven tijdstip. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Haalt jaar op voor het opgegeven tijdstip. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Construeert specifieke gregoriaanse kalender. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Controleert of de dag een schrikkeldag is. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Controleert of de maand een schrikkelmaand is. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Controleert of de maand een schrikkelmaand is. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Controleert of de maand een schrikkelmaand is. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Controleert of het jaar een schrikkeljaar is. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Controleert of het jaar een schrikkeljaar is. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Controleert of het jaar een schrikkeljaar is. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Controleert jaar-, maand-, dag- en era-waarden. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment-operator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Haalt alleen-lezen versie van de kalender op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Stelt Gregoriaans kalendertype in. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Stelt het laatste jaar in dat kan worden weergegeven met twee cijfers. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th template-argument in op een zwakke pointer (in plaats van shared). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converteert het jaar naar een 4-cijferig jaar met behulp van de TwoDigitYearMax-eigenschap. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [ADEra](./adera/) | Huidige era. |

## Zie ook

* Klasse [Calendar](../calendar/)
* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)