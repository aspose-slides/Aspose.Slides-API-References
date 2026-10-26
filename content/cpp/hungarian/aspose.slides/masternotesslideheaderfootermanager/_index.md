---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides a C++ API hivatkozása
description: A menedzsert képviseli, amely a mester jegyzetdia lábléc, dátum-idő és oldalszám helyőrzőinek, valamint az összes gyermekhelyőrzőnek a viselkedését tartalmazza. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon találhatók. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.
type: docs
weight: 4460
url: /hu/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager osztály


A menedzser, amely a mester jegyzetdia lábléc, dátum-idő, oldalszám helyőrzőket és az összes gyermekhelyőrzőt tartalmazza, kezeli. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Visszaadja, hogy dátum-idő helyőrző jelen van-e. Olvasás**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Visszaadja, hogy lábléc helyőrző jelen van-e. Olvasás **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Visszaadja, hogy fejléc helyőrző jelen van-e. Olvasás **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Visszaadja, hogy oldalszám helyőrző jelen van-e. Olvasás**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referencia-számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# `is` operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlít egy értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Szöveget állít be a mester dia dátum-idő helyőrzőjébe és az összes gyermek dátum-idő helyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Megváltoztatja a mester dia dátum-idő helyőrző és az összes gyermek dátum-idő helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Szöveget állít be a dia dátum-idő helyőrzőjébe. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Megváltoztatja a dia dátum-idő helyőrző láthatóságát. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Szöveget állít be a mester dia lábléc helyőrzőjébe és az összes gyermek lábléc helyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Megváltoztatja a mester dia lábléc helyőrző és az összes gyermek lábléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Szöveget állít be a dia lábléc helyőrzőjébe. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Megváltoztatja a dia lábléc helyőrző láthatóságát. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | Szöveget állít be a mester jegyzetdia fejléc helyőrzőjébe és az összes gyermek fejléc helyőrzőbe. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | Megváltoztatja a mester jegyzetdia fejléc helyőrző és az összes gyermek fejléc helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Szöveget állít be a dia fejléc helyőrzőjébe. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Megváltoztatja a dia fejléc helyőrző láthatóságát. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Megváltoztatja a mester dia oldalszám helyőrző és az összes gyermek oldalszám helyőrző láthatóságát. A gyermekhelyőrzők olyan helyőrzők, amelyek a függő jegyzetdíákon vannak elhelyezve. A függő jegyzetdiák a mester jegyzetdiát használják és tőle függenek. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Megváltoztatja a dia oldalszám helyőrző láthatóságát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóra (nem megosztott) állítja be. Lehetővé teszi a mutatók átkapcsolását tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterláncra konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Lemosolja az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Osztály [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)