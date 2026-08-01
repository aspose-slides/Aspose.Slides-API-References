---
title: JapaneseCalendar
second_title: Aspose.Slides voor C++ API-referentie
description: "Japanse kalender. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 183
url: /nl/system.globalization/japanesecalendar/
---
## JapaneseCalendar klasse


Japanse kalender. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten kan veroorzaken. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Maakt een kopie van het huidige object en retourneert een shared pointer. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Haalt algoritmetype op. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Haalt index van de huidige era op. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Haalt waarde van de huidige era op. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Haalt lijst van periodes op die in de kalender bestaan. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Controleert of de kalender alleen-lezen is. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaal tijdstip dat door de kalender wordt ondersteund. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaal tijdstip dat door de kalender wordt ondersteund. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Haalt het laatste jaar op dat met twee cijfers kan worden weergegeven. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Haalt dag van de maand op voor het opgegeven tijdstip. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Haalt dag van de week op voor het opgegeven tijdstip. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Haalt dag van het jaar op voor het opgegeven tijdstip. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Haalt aantal dagen in een specifieke maand op. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Haalt aantal dagen in een specifieke maand op. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Haalt aantal dagen in een specifieke maand op. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Haalt aantal dagen in een specifiek jaar op. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Haalt aantal dagen in een specifiek jaar op. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Haalt aantal dagen in een specifiek jaar op. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Haalt era op voor het opgegeven tijdstip. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Haalt uren op voor het opgegeven tijdstip. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Haalt de sprongmaand op voor het opgegeven jaar. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Haalt de sprongmaand op voor het opgegeven jaar. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Haalt de sprongmaand op voor het opgegeven jaar. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Haalt milliseconden op voor het opgegeven tijdstip. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Haalt minuten op voor het opgegeven tijdstip. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Haalt maand op voor het opgegeven tijdstip. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Haalt aantal maanden op in het opgegeven jaar. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-informatie. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-informatie. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Haalt seconden op voor het opgegeven tijdstip. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Haalt week van het jaar op voor het opgegeven tijdstip. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Haalt jaar op voor het opgegeven tijdstip. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# 'is'-operator. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Controleert of de dag een schrikkeldag is. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Controleert of de maand een schrikkeldag is. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Controleert of de maand een schrikkeldag is. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Controleert of de maand een schrikkeldag is. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Controleert of het jaar een schrikkeljaar is. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Controleert of het jaar een schrikkeljaar is. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Controleert of het jaar een schrikkeljaar is. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Controleert de waarden van jaar, maand, dag en era. |
|  [JapaneseCalendar](./japanesecalendar/)() | Constructor. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewaakobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Haalt alleen-lees versie van de kalender op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Stelt het laatste jaar in dat met twee cijfers kan worden weergegeven. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/)-object uit componenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converteert het jaar naar een 4-cijferig jaar met behulp van de TwoDigitYearMax-eigenschap. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewaakobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)