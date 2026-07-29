---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides för C++ API-referens
description: "Östasian lunisolär kalender. Objekt av den här klassen ska endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller assertionsfel. Wrappa alltid den här klassen i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 105
url: /sv/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar klass


East-asian lunisolar calendar. Objects of this klass should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this klass into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Metoder

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Lägger till dagar till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Lägger till timmar till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Lägger till millisekunder till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Lägger till minuter till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Lägger till månader till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Lägger till sekunder till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Lägger till veckor till tidspunkt. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Lägger till år till tidspunkt. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-information. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Skapar en kopia av det aktuella objektet och returnerar en delad pekare till det. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | RTTI-information. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Hämtar index för den aktuella eran. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Hämtar värdet för den aktuella eran. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Hämtar lista över eraer som finns i kalendern. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Hämtar kalenderidentifierare. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Kontrollerar om kalendern är skrivskyddad. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Maximal tidpunkt som stöds av kalendern. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Minimal tidpunkt som stöds av kalendern. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Hämtar det sista år som kan representeras med två siffror. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Hämtar himmelsk stam. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Hämtar dag i månad för den angivna tidspunkten. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Hämtar veckodag för den angivna tidspunkten. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Hämtar dag på året för den angivna tidspunkten. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Hämtar antalet dagar i specifik månad. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Hämtar antalet dagar i specifik månad. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Hämtar antalet dagar i specifikt år. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Hämtar antalet dagar i specifikt år. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Hämtar era för den angivna tidspunkten. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Hämtar timmar för den angivna tidspunkten. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Hämtar skottmånad för det angivna året. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Hämtar skottmånad för det angivna året. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Hämtar millisekunder för den angivna tidspunkten. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Hämtar minuter för den angivna tidspunkten. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Hämtar månad för den angivna tidspunkten. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Hämtar antalet månader i det angivna året. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Hämtar antalet månader i det angivna året. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Hämtar sekunder för den angivna tidspunkten. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Hämtar året i den sextagenära cykeln. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Hämtar jordisk gren. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Hämtar vecka på året för den angivna tidspunkten. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Hämtar år för den angivna tidspunkten. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Kontrollerar om dagen är en skottdag. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Kontrollerar om dagen är en skottdag. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Kontrollerar om månaden är en skottmånad. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Kontrollerar om månaden är en skottmånad. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Kontrollerar om året är ett skottår. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Kontrollerar om året är ett skottår. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Kontrollerar år, månad, dag och era-värden. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Hämtar skrivskyddad version av kalendern. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ställer in det sista året som kan representeras med två siffror. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konverterar året till fyrsiffrigt år med hjälp av TwoDigitYearMax-egenskapen. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |
## Se även

* Klass [Calendar](../calendar/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)