---
title: TimeZoneInfo
second_title: Aspose.Slides C++ API referenciája
description: "Egy adott időzónát leíró információt reprezentál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátorral, mivel futásidejű hibákhoz és/vagy állítási hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek."
type: docs
weight: 1340
url: /hu/system/timezoneinfo/
---
## TimeZoneInfo osztály


Az adott időzónát leíró információt reprezentálja. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az new operátorral, mivel futásidejű hibákhoz és/vagy állítási hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | Törli a gyorsítótárazott időzóna adatokat. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) időt egy időzónából a másikba. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) időt a megadott időzónában. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) időt a megadott időzónában. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) időt a megadott időzónában. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) időt a megadott időzónában. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) időt a megadott időzónában. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Átalakítja az UTC időt egy megadott időzónába. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Átalakítja az időt UTC időre. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | Átalakítja az időt UTC időre. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | Átalakítja az időt UTC időre. CSAK BELSŐ HASZNÁLATRA. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | Egy egyedi időzónát hoz létre. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | Egy egyedi időzónát hoz létre. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | Egy egyedi időzónát hoz létre. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | Megállapítja, hogy a jelenlegi és a megadott objektumok egyenlők-e. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | CSAK BELSŐ CÉLRA. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | Lekéri a megadott azonosítóval rendelkező időzónát. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | Visszaad egy [TimeSpan](../timespan/) példányt, amely a jelenlegi időzóna szabványos ideje és az UTC idő közötti időintervallumot reprezentálja. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | Lekéri a jelenlegi időzóna nyári időszámának nevét. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | Lekéri a jelenlegi időzóna nevét. |
| [String](../string/) [get_Id](./get_id/)() const | Visszaadja a jelenlegi objektum által reprezentált időzóna azonosítóját. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | Visszaad egy [TimeZoneInfo](./) példányt, amely egy helyi időzónát reprezentál. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | Lekéri a jelenlegi időzóna szabványos időnek a nevét. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Lekéri azt a jelzőt, amely jelzi, hogy az időzónának van-e nyári időszám szabálya. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | Visszaad egy [TimeZoneInfo](./) példányt, amely egy UTC időzónát reprezentál. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | Visszaad egy tömböt, amely **AdjustmentRule** objektumokból áll, és a jelenlegi [TimeZoneInfo](./) objektumra alkalmazott módosítási szabályokat reprezentálja. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | Lekéri az UTC dátumokat és időpontokat, amelyekre egy megadott dátum és idő leképezhető. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Lekéri az UTC dátumokat és időpontokat, amelyekre egy megadott dátum és idő leképezhető. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| int [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-ét. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | Lekéri a helyi rendszeren elérhető összes időzóna rendezett gyűjteményét. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | Kiszámítja a különbséget a jelenlegi időzóna és az UTC időzóna között egy megadott dátum és idő esetén. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Kiszámítja a különbséget a jelenlegi időzóna és az UTC időzóna között egy megadott dátum és idő esetén. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Belső segédfüggvény, amely visszaadja az UTC időeltolódást egy megadott időzónában lévő UTC-dátum-idő számára. CSAK BELSŐ HASZNÁLATRA. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | Belső segédfüggvény, amely visszaadja az UTC időeltolódást egy megadott időzónában lévő UTC-dátum-idő számára. CSAK BELSŐ HASZNÁLATRA. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | Kiszámítja a különbséget a jelenlegi időzóna és az UTC időzóna között egy megadott dátum és idő esetén. CSAK BELSŐ HASZNÁLATRA. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | Ellenőrzi, hogy a jelenlegi és egy másik időzóna ugyanazokkal a módosítási szabályokkal rendelkezik-e. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | Ellenőrzi, hogy a megadott dátum és idő nem egyértelmű-e, és több UTC időpontra is leképezhető-e. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Ellenőrzi, hogy a megadott dátum és idő nem egyértelmű-e, és több UTC időpontra is leképezhető-e. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | Ellenőrzi, hogy a megadott dátum és idő beleesik-e a nyári időszám tartományába. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Ellenőrzi, hogy a megadott dátum és idő beleesik-e a nyári időszám tartományába. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | Ellenőrzi, hogy a megadott dátum és idő beleesik-e a nyári időszám tartományába. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | Ellenőrzi, hogy a megadott dátum és idő érvénytelen-e. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentry objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-alapú összehasonlítás egy értéktípusú objektum és a nullptr között. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja a n'th sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | Segédfüggvény, amely egy évet és egy **TransitionTime**-t [DateTime](../datetime/)-é alakít át. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) konstrukciót. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | Egy alias egy megosztott mutatóhoz, amely egy **AdjustmentRule** osztály példányára mutat. |

## Lásd még

* Osztály [IEquatable](../iequatable/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)