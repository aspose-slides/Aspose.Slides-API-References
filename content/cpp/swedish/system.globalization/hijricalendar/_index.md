---
title: HijriCalendar
second_title: Aspose.Slides för C++ API-referens
description: "Hijri-kalender. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 157
url: /sv/system.globalization/hijricalendar/
---
## HijriCalendar klass

Hijri-kalender. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HijriCalendar : public System::Globalization::Calendar
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Lägger till dagar till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Lägger till timmar till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Lägger till millisekunder till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Lägger till minuter till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Lägger till månader till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Lägger till sekunder till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Lägger till veckor till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Lägger till år till tidpunkten. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-information. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet och returnerar en delad pekare till det. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalssjämförelse i C#-stil där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalssjämförelse i C#-stil för double där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Hämtar algoritmtyp. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Hämtar index för den aktuella eran. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Hämtar värdet för den aktuella eran. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Hämtar lista över eraer som finns i kalendern. |
| int [get_HijriAdjustment](./get_hijriadjustment/)() const | Hämtar hijri-justering. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontrollerar om kalendern är skrivskyddad. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Hämtar det sista året som kan representeras med två siffror. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Hämtar dag i månad för den angivna tidpunkten. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Hämtar veckodag för den angivna tidpunkten. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Hämtar dag på året för den angivna tidpunkten. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Hämtar antalet dagar i en specifik månad. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Hämtar antalet dagar i en specifik månad. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Hämtar antalet dagar i ett specifikt år. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Hämtar antalet dagar i ett specifikt år. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Hämtar era för den angivna tidpunkten. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Hämtar timmar för den angivna tidpunkten. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skottmånaden för det angivna året. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI-information. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI-information. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Hämtar millisekunder för den angivna tidpunkten. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Hämtar minuter för den angivna tidpunkten. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Hämtar månad för den angivna tidpunkten. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Hämtar antalet månader i det angivna året. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Hämtar antalet månader i det angivna året. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Hämtar sekunder för den angivna tidpunkten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Hämtar vecka på året för den angivna tidpunkten. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Hämtar år för den angivna tidpunkten. |
|  [HijriCalendar](./hijricalendar/)() | Konstruktor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är skottdag. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är skottdag. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Kontrollerar om dagen är skottdag. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Kontrollerar om månaden är skottmånad. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är skottmånad. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Kontrollerar om månaden är skottmånad. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är skottår. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är skottår. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Kontrollerar om året är skottår. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Kontrollerar år, månad, dag och eravärden. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Hämtar en skrivskyddad version av kalendern. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_HijriAdjustment](./set_hijriadjustment/)(int) | Ställer in hijri-justering. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ställer in det sista året som kan representeras med två siffror. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstrukterar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstrukterar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konverterar året till ett fyrsiffrigt år med hjälp av egenskapen TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [HijriEra](./hijriera/) | Aktuell hijri-era. |

## Se även

* Klass [Calendar](../calendar/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)