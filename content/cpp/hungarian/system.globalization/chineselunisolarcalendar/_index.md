---
title: ChineseLunisolarCalendar
second_title: Aspose.Slides C++ API referencia
description: "Kínai holdnapévi naptár. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 27
url: /hu/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar osztály

Kínai holdnapévi naptár. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stacken vagy az operator new használatával, mivel ez futási hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Napokat ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Órákat ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Milliszekundumokat ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Perceket ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Hónapokat ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Másodperceket ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Heteket ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Éveket ad a időponthoz. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI információ. |
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | Alapértelmezett konstruktor. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Létrehozza a jelenlegi objektum másolatát, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI információ. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | A jelenlegi korszak indexét adja vissza. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | A jelenlegi korszak értékét adja vissza. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | A naptárban létező korszakok listáját adja vissza. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak-olvasású-e. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | A naptár által támogatott legnagyobb időpontot adja vissza. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | A naptár által támogatott legkisebb időpontot adja vissza. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Az a legutolsó év, amelyet egy 2-jegyű szám ábrázolhat. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Az égitest ágat adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz tartozó referenciakölcsönző adatstruktúrát adja vissza. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó hónap napját adja vissza. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó hét napját adja vissza. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó év napját adja vissza. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | A megadott hónap napjainak számát adja vissza. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | A megadott hónap napjainak számát adja vissza. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | A megadott hónap napjainak számát adja vissza. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | A megadott év napjainak számát adja vissza. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | A megadott év napjainak számát adja vissza. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó korszakot adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó órákat adja vissza. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | A megadott év szökőhónapját adja vissza. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | A megadott év szökőhónapját adja vissza. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | A megadott év szökőhónapját adja vissza. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó milliszekundumokat adja vissza. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó perceket adja vissza. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó hónapot adja vissza. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | A megadott évben lévő hónapok számát adja vissza. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI információ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI információ. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó másodperceket adja vissza. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | A szexagenári ciklusban levő év számát adja vissza. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | A földi ágat adja vissza. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | A megadott időponthoz tartozó hét számát adja vissza. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó évet adja vissza. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a megadott típusú-e. A C# 'is' operátor analógja. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ellenőrzi, hogy az év szökőév-e. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ellenőrzi az év, hónap, nap és korszak értékeket. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítást valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | A naptár csak-olvasású verzióját adja vissza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális megvalósítása string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális megvalósítása stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciakészlet számlálóját a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja a legutolsó évet, amelyet egy 2-jegyű szám ábrázolhat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett) állítja. Lehetővé teszi a mutatók gyengévé alakítását konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciakészlet aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciakészlet számlálóját. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciakészlet számlálóját. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az összetevőkből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az összetevőkből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Az évet 4-jegyű évre konvertálja a TwoDigitYearMax tulajdonság alapján. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok sztringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciakészlet számlálóját. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciakészlet számlálóját. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | Aktuális kínai korszak. |

## Lásd még

* Osztály [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Névterület [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)