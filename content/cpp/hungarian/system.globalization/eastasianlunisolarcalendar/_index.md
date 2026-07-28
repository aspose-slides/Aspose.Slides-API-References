---
title: EastAsianLunisolarCalendar
second_title: Aspose.Slides for C++ API Referencia
description: "Kelet-ázsiai hold-földi naptár. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 105
url: /hu/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar osztály

East-asian lunisolar calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Hozzáad napokat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Hozzáad órákat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Hozzáad ezredmásodpercet az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Hozzáad perceket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Hozzáad hónapokat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Hozzáad másodperceket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Hozzáad heteket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Hozzáad éveket az időponthoz. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI információ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Létrehoz a jelenlegi objektum egy másolatát, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | RTTI információ. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Lekéri a jelenlegi korszak indexét. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Lekéri a jelenlegi korszak értékét. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Lekéri a naptárban létező korszakok listáját. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Lekéri a naptár azonosítóját. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak olvasható-e. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | A naptár által támogatott legnagyobb időpont. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | A naptár által támogatott legkisebb időpont. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Lekéri az utolsó évet, amelyet kétjegyű formában lehet ábrázolni. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Lekéri az égi ágat. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Lekéri a napot a hónapban a megadott időponthoz. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Lekéri a hét napját a megadott időponthoz. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Lekéri a napot az évben a megadott időponthoz. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Lekéri a napok számát egy adott hónapban. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Lekéri a napok számát egy adott hónapban. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Lekéri a napok számát egy adott évben. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Lekéri a napok számát egy adott évben. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Lekéri a korszakot a megadott időponthoz. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Lekéri az órákat a megadott időponthoz. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Lekéri a szökőhónapot a megadott évre. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Lekéri a szökőhónapot a megadott évre. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Lekéri a milliszekundumokat a megadott időponthoz. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Lekéri a perceket a megadott időponthoz. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Lekéri a hónapot a megadott időponthoz. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Lekéri a hónapok számát a megadott évben. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Lekéri a hónapok számát a megadott évben. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Lekéri a másodperceket a megadott időponthoz. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Lekéri az évet a hatvanéves ciklusban. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Lekéri a földi ágat. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Lekéri az év hétjét a megadott időponthoz. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Lekéri az évet a megadott időponthoz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Ellenőrzi, hogy az év szökőév-e. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ellenőrzi az év, hónap, nap és korszak értékeit. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelő operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Lekéri a naptár csak olvasható változatát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja az utolsó évet, amelyet kétjegyű számmal lehet ábrázolni. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók konténerekben való átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az összetevőkből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az összetevőkből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Átkonvertálja az évet négyjegyű évre a TwoDigitYearMax tulajdonság használatával. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Calendar](../calendar/)
* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)