---
title: TaiwanCalendar
second_title: Aspose.Slides C++ API referencia
description: "Tajvani naptár. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 326
url: /hu/system.globalization/taiwancalendar/
---
## TaiwanCalendar osztály


Tajvani naptár. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek.

```cpp
class TaiwanCalendar : public System::Globalization::Calendar
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Napokat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Órákat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Ezredmásodpercet ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Perceket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Hónapokat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Másodperceket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Heteket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Éveket ad az időponthoz. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI információ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Létrehoz egy másolatot a jelenlegi objektumról, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Algoritmus típus lekérése. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Az aktuális korszak indexének lekérése. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Az aktuális korszak értékének lekérése. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | A naptárban létező korszakok listájának lekérése. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak olvasható-e. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | A naptár által támogatott legnagyobb időpont. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | A naptár által támogatott legkisebb időpont. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Az utolsó évet adja vissza, amelyet egy 2 számjegyű kifejezéssel lehet ábrázolni. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz kapcsolódó referenciaszámláló adatstruktúra lekérése. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó nap számának lekérése a hónapban. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó nap számának lekérése a hét napja szerint. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó nap számának lekérése az évben. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | A megadott hónap napjainak számának lekérése. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | A megadott hónap napjainak számának lekérése. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | A megadott hónap napjainak számának lekérése. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | A megadott év napjainak számának lekérése. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | A megadott év napjainak számának lekérése. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | A megadott év napjainak számának lekérése. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó korszak lekérése. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-ölését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó órák lekérése. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | A megadott év szökőhónapjának lekérése. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | A megadott év szökőhónapjának lekérése. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | A megadott év szökőhónapjának lekérése. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó ezredmásodpercek lekérése. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó percek lekérése. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó hónap lekérése. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | A megadott évben lévő hónapok számának lekérése. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI információ. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI információ. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | A megadott időponthoz tartozó másodpercek lekérése. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusának lekérése. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | A megadott időponthoz tartozó hét lekérése az évben. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | A megadott időponthoz tartozó év lekérése. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ellenőrzi, hogy a nap szökőév-nap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ellenőrzi, hogy a nap szökőév-nap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ellenőrzi, hogy a nap szökőév-nap-e. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ellenőrzi, hogy az év szökőév-e. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ellenőrzi az év, hónap, nap és korszak értékeket. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | A naptár csak olvasható változatának lekérése. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot összehasonlít referenciával a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | A megosztott referenciaszámláló csökkentése a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja az utolsó évet, amelyet egy 2 számjegyű kifejezéssel lehet ábrázolni. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra állítja (a megosztott helyett). Lehetővé teszi a mutatók cseréjét a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékének lekérése. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Megnöveli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [TaiwanCalendar](./taiwancalendar/)() | Konstruktor. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Létrehozza a [DateTime](../../system/datetime/) objektumot az alkotóelemekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az alkotóelemekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Létrehozza a [DateTime](../../system/datetime/) objektumot az alkotóelemekből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Az évet 4 számjegyre konvertálja a TwoDigitYearMax tulajdonság használatával. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | A gyenge referenciaszámláló növelése. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | A gyenge referenciaszámláló csökkentése. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Calendar](../calendar/)
* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)