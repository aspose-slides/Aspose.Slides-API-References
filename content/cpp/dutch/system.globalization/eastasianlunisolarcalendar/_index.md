---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides voor C++ API Referentie
description: "Oost-Aziatische lunisolaire kalender. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, aangezien dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 105
url: /nl/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar klasse

Oost-Aziatische lunisolaire kalender. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, aangezien dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
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
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Maakt een kopie van het huidige object en retourneert een gedeelde pointer hiernaar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | RTTI-informatie. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Haal de index van de huidige era op. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Haal de waarde van de huidige era op. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Haal lijst op van bestaande era's in de kalender. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Haalt kalenderidentificatie op. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Controleert of de kalender alleen-lezen is. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Maximaal tijdstip dat ondersteund wordt door de kalender. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Minimaal tijdstip dat ondersteund wordt door de kalender. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Haalt het laatste jaar op dat kan worden weergegeven met twee cijfers. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Haalt de hemelse stam op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Haalt dag van de maand op voor het opgegeven tijdstip. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Haalt dag van de week op voor het opgegeven tijdstip. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Haalt dag van het jaar op voor het opgegeven tijdstip. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Haalt aantal dagen op in een specifieke maand. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Haalt aantal dagen op in een specifieke maand. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Haalt aantal dagen op in een specifiek jaar. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Haalt aantal dagen op in een specifiek jaar. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Haalt era op voor het opgegeven tijdstip. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Haalt uren op voor het opgegeven tijdstip. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Haalt de schrikkelmaand op voor het opgegeven jaar. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Haalt de schrikkelmaand op voor het opgegeven jaar. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Haalt milliseconden op voor het opgegeven tijdstip. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Haalt minuten op voor het opgegeven tijdstip. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Haalt maand op voor het opgegeven tijdstip. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Haalt aantal maanden op in het opgegeven jaar. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Haalt aantal maanden op in het opgegeven jaar. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Haalt seconden op voor het opgegeven tijdstip. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Haalt het jaar op in de sexagesimale cyclus. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Haalt de terrestrische tak op. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Haalt week van het jaar op voor het opgegeven tijdstip. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Haalt jaar op voor het opgegeven tijdstip. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Controleert of de dag een schrikkeldag is. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Controleert of de maand een schrikkelmaand is. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Controleert of de maand een schrikkelmaand is. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Controleert of het jaar een schrikkeljaar is. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Controleert of het jaar een schrikkeljaar is. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Controleert de waarden van jaar, maand, dag en era. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert niets, eigenlijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Kopieert niets, eigenlijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Haalt alleen-lezen versie van de kalender op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-typed object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Stelt het laatste jaar in dat kan worden weergegeven met twee cijfers. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus om te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/) object uit componenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Construeert [DateTime](../../system/datetime/) object uit componenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converteert het jaar naar een 4-cijferig jaar met behulp van de TwoDigitYearMax eigenschap. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Calendar](../calendar/)
* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)