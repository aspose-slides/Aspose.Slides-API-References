---
title: KoreanCalendar
second_title: Aspose.Slides C++ API referencia
description: "Koreai naptár. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 222
url: /hu/system.globalization/koreancalendar/
---
## KoreanCalendar osztály


Koreai naptár. Ennek az osztálynak az objektumait csak a(z) [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály függvényeknek argumentumként történő átadásához.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## Methods

| Metódus | Leírás |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Létrehoz egy másolatot az aktuális objektumból, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritmus típust kap. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Az aktuális korszak indexét adja vissza. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Az aktuális korszak értékét adja vissza. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | A naptárban létező korszakok listáját adja vissza. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak olvasható-e. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | A naptár által támogatott legnagyobb időpont. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | A naptár által támogatott legkisebb időpont. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Az az utolsó év, amelyet 2 számjeggyel lehet ábrázolni. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát adja vissza. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó hónap napját adja vissza. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó hét napját adja vissza. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó év napját adja vissza. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Az adott hónap napjainak számát adja vissza. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Az adott hónap napjainak számát adja vissza. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Az adott hónap napjainak számát adja vissza. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Az adott év napjainak számát adja vissza. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Az adott év napjainak számát adja vissza. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Az adott év napjainak számát adja vissza. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó korszakot adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó órákat adja vissza. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Az adott év szökőhónapját adja vissza. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Az adott év szökőhónapját adja vissza. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Az adott év szökőhónapját adja vissza. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó milliszekundumokat adja vissza. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó perceket adja vissza. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó hónapot adja vissza. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Az adott év hónapjainak számát adja vissza. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI információ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI információ. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó másodperceket adja vissza. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Az adott időponthoz tartozó év hetét adja vissza. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Az adott időponthoz tartozó évet adja vissza. |
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
|  [KoreanCalendar](./koreancalendar/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoláskonstruálását. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoláskonstruálását. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | A naptár csak olvasható változatát adja vissza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja a értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja az utolsó évet, amelyet 2 számjeggyel lehet ábrázolni. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá állítja (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | [DateTime](../../system/datetime/) objektumot hoz létre komponensekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) objektumot hoz létre komponensekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) objektumot hoz létre komponensekből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Az évet 4 számjegyű évre konvertálja a TwoDigitYearMax tulajdonság használatával. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Fields

| Mező | Leírás |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | Aktuális koreai korszak. |
## Lásd még

* Osztály [Calendar](../calendar/)
* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)