---
title: JapaneseCalendar
second_title: Aspose.Slides C++ API referencia
description: "Japán naptár. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhíváshoz."
type: docs
weight: 183
url: /hu/system.globalization/japanesecalendar/
---
## JapaneseCalendar osztály

Japán naptár. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Hozzáad napokat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Hozzáad órákat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Hozzáad ezredmásodpercet az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Hozzáad perceket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Hozzáad hónapokat az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Hozzáad másodperceket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Hozzáad heteket az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Hozzáad éveket az időponthoz. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI információ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Létrehoz egy másolatot a jelenlegi objektumról, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, mégis az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, mégis az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Lekéri az algoritmus típusát. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Lekéri az aktuális korszak indexét. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Lekéri az aktuális korszak értékét. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Lekéri a naptárban létező korszakok listáját. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak olvasható-e. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | A naptár által támogatott legnagyobb időpont. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | A naptár által támogatott legkisebb időpont. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Lekéri a legutolsó évet, amelyet 2 számjeggyel lehet ábrázolni. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Lekéri a napot a hónapban a megadott időponthoz. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Lekéri a hét napját a megadott időponthoz. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Lekéri a napot az évben a megadott időponthoz. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Lekéri egy adott hónap napjainak számát. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Lekéri egy adott hónap napjainak számát. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Lekéri egy adott hónap napjainak számát. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Lekéri egy adott év napjainak számát. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Lekéri egy adott év napjainak számát. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Lekéri egy adott év napjainak számát. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Lekéri a korszakot a megadott időponthoz. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Lekéri az órákat a megadott időponthoz. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Lekéri a szökőhónapot a megadott évhez. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Lekéri a szökőhónapot a megadott évhez. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Lekéri a szökőhónapot a megadott évhez. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Lekéri az ezredmásodpercet a megadott időponthoz. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Lekéri a perceket a megadott időponthoz. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Lekéri a hónapot a megadott időponthoz. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Lekéri a hónapok számát a megadott évben. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI információ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI információ. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Lekéri a másodperceket a megadott időponthoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Lekéri a hét számát az évben a megadott időponthoz. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Lekéri az évet a megadott időponthoz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
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
|  [JapaneseCalendar](./japanesecalendar/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializál egy új objektumot, és lehetővé teszi az alosztályok másolásalapú konstrukcióját. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Lekéri a naptár csak-olvasású változatát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja az utolsó évet, amely 2 számjeggyel ábrázolható. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n. sablonargumentumot gyenge mutatóval (nem megosztottal) állítja be. Lehetővé teszi a mutatók módosítását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Létrehozza a [DateTime](../../system/datetime/) objektumot komponensekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot komponensekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot komponensekből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Az évet 4 számjegyű évre konvertálja a TwoDigitYearMax tulajdonság használatával. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstruktumot. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Calendar](../calendar/)
* Névterület [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)