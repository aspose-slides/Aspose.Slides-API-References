---
title: TaiwanLunisolarCalendar
second_title: Aspose.Slides för C++ API-referens
description: "Taiwan lunisolarkalender. Ej implementerad. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omge alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 339
url: /sv/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar klass

Taiwan lunisolarkalender. Ej implementerad. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omge alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
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
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI-information. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Hämtar index för aktuell era. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Hämtar värdet för aktuell era. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Hämtar lista över eror som finns i kalendern. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontrollerar om kalendern är skrivskyddad. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximal tidpunkt som stöds av kalendern. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimal tidpunkt som stöds av kalendern. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Hämtar det sista året som kan representeras med två siffror. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Hämtar himmelsk stam. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Hämtar dag i månad för den angivna tidpunkten. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Hämtar veckodag för den angivna tidpunkten. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Hämtar dag på året för den angivna tidpunkten. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Hämtar antal dagar i en specifik månad. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Hämtar antal dagar i ett specifikt år. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Hämtar antal dagar i ett specifikt år. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Hämtar era för den angivna tidpunkten. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Hämtar timmar för den angivna tidpunkten. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Hämtar skottmånaden för det angivna året. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Hämtar skottmånaden för det angivna året. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Hämtar skottmånaden för det angivna året. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Hämtar millisekunder för den angivna tidpunkten. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Hämtar minuter för den angivna tidpunkten. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Hämtar månad för den angivna tidpunkten. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Hämtar antal månader i det angivna året. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-information. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-information. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Hämtar sekunder för den angivna tidpunkten. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Hämtar året i den sextagenära cykeln. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Hämtar jordgren. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Hämtar vecka på året för den angivna tidpunkten. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Hämtar år för den angivna tidpunkten. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Kontrollerar om dagen är skottdag. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är skottdag. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Kontrollerar om dagen är skottdag. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Kontrollerar om månaden är skottmånad. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Kontrollerar om månaden är skottmånad. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Kontrollerar om året är skottår. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är skottår. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Kontrollerar om året är skottår. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Kontrollerar värdena för år, månad, dag och era. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Hämtar skrivskyddad version av kalendern. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Sätter det sista året som kan representeras med två siffror. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n't:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
|  [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | Konstruktor. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konverterar året till fyrsiffrigt år med egenskapen TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |
## Se även

* Klass [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)