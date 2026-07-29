---
title: Calendar
second_title: Aspose.Slides för C++ API-referens
description: "Kalender som definierar hur datum hanteras, beräknas, formateras osv. Setter-operationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid denna klass i System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.globalization/calendar/
---
## Calendar klass

[Calendar](./) som definierar hur datum hanteras, beräknas, formateras osv. Setter-operationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Calendar : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Lägger till dagar till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Lägger till timmar till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Lägger till millisekunder till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Lägger till minuter till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Lägger till månader till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Lägger till sekunder till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Lägger till veckor till tidpunkten. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Lägger till år till tidpunkten. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | RTTI-information. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Skapar en kopia av det aktuella objektet och returnerar en delad pekare till det. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Hämtar algoritmtyp. |
| int [get_CurrentEra](./get_currentera/)() const | Hämtar index för aktuell era. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Hämtar värde för aktuell era. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Hämtar lista över eror som finns i kalendern. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Hämtar kalenderidentifierare. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om kalendern är skrivskyddad. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Maximal tidpunkt som stöds av kalendern. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Minimal tidpunkt som stöds av kalendern. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Hämtar det sista året som kan representeras med två siffror. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Hämtar dag i månad för den angivna tidpunkten. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Hämtar veckodag för den angivna tidpunkten. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Hämtar dag på år för den angivna tidpunkten. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Hämtar antal dagar i en specifik månad. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Hämtar antal dagar i ett specifikt år. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Hämtar antal dagar i ett specifikt år. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Hämtar era för den angivna tidpunkten. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Hämtar timmar för den angivna tidpunkten. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Hämtar skottmånaden för det angivna året. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Hämtar skottmånaden för det angivna året. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Hämtar millisekunder för den angivna tidpunkten. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Hämtar minuter för den angivna tidpunkten. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Hämtar månad för den angivna tidpunkten. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Hämtar antal månader i det angivna året. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Hämtar antal månader i det angivna året. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Hämtar sekunder för den angivna tidpunkten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Hämtar vecka på året för den angivna tidpunkten. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Hämtar år för den angivna tidpunkten. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Kontrollerar om dagen är skott. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Kontrollerar om dagen är skott. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Kontrollerar om månaden är skott. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Kontrollerar om månaden är skott. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Kontrollerar om året är skott. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Kontrollerar om året är skott. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Kontrollerar år, månad, dag och era-värden. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Hämtar skrivskyddad version av kalendern. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Sätter det sista året som kan representeras med två siffror. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Konstruerar [DateTime](../../system/datetime/)-objekt från komponenter. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Konverterar året till fyrsiffrigt år med hjälp av egenskapen TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [ICloneable](../../system/icloneable/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)