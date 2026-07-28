---
title: KoreanLunisolarCalendar
second_title: Aspose.Slides C++ API Referencia
description: "Koreai holdnapló naptár. Nem implementált. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 235
url: /hu/system.globalization/koreanlunisolarcalendar/
---
## KoreanLunisolarCalendar osztály


Koreai holdnapló naptár. Nincs megvalósítva. Ennek az osztálynak a példányait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával kell lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum funkciók argumentumaként történő átadására.

```cpp
class KoreanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Napokat ad a időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Órákat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Milliszekundumokat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Perceket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Hónapokat ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Másodperceket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Heteket ad az időponthoz. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Éveket ad az időponthoz. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI információ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Létrehoz egy másolatot a jelenlegi objektumról, és visszaad egy megosztott mutatót rá. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRtt iBase\&, void **) const | Csak belső célokra. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI információ. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | A jelenlegi éra indexét kapja. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | A jelenlegi éra értékét kapja. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Az naptárban létező érák listáját kapja. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ellenőrzi, hogy a naptár csak olvasható-e. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | A naptár által támogatott legnagyobb időpont. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | A naptár által támogatott legkisebb időpont. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | A kétjegyűvel ábrázolható legutolsó évet kapja. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Az égi szárat kapja. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referencia számláló adatstruktúrát kapja. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó hónap napját kapja. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó hét napját kapja. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó év napját kapja. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Az adott hónap napjainak számát kapja. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Az adott hónap napjainak számát kapja. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Az adott év napjainak számát kapja. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Az adott év napjainak számát kapja. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó érat kapja. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyéni objektumok hash-elését. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó órákat kapja. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Az adott év szökőhónapját kapja. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI információ. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI információ. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó milliszekundumokat kapja. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó perceket kapja. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó hónapot kapja. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Az adott év hónapjainak számát kapja. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Az adott év hónapjainak számát kapja. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó másodperceket kapja. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | A hatvanéves ciklusban az évet kapja. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | A földi ágat kapja. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát kapja. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Az adott időponthoz tartozó hét számát kapja. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Az adott időponthoz tartozó évet kapja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ellenőrzi, hogy a nap szökőnap-e. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ellenőrzi, hogy a hónap szökőhónap-e. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ellenőrzi, hogy az év szökőév-e. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ellenőrzi, hogy az év szökőév-e. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ellenőrzi az év, hónap, nap és éra értékeket. |
|  [KoreanLunisolarCalendar](./koreanlunisolarcalendar/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolópéldányosítását. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolópéldányosítását. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | A naptár csak olvasható változatát kapja. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Beállítja a kétjegyűvel ábrázolható legutolsó évet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerekben való gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló aktuális értékét kapja. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) objektumot hoz létre komponensekből. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | [DateTime](../../system/datetime/) objektumot hoz létre komponensekből. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Átalakítja az évet négyjegyű évre a TwoDigitYearMax tulajdonság használatával. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [GregorianEra](./gregorianera/) | A jelenlegi gregorián éra. |

## Lásd még

* Osztály [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Névterület [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)