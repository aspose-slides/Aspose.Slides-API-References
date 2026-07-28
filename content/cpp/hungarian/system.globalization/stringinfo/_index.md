---
title: StringInfo
second_title: Aspose.Slides for C++ API Referencia
description: "Karakterlánc részeinek bejárásához használható felosztó. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvényeknek argumentumként való átadásához."
type: docs
weight: 313
url: /hu/system.globalization/stringinfo/
---
## StringInfo osztály

Felosztó a karakterlánc részeinek bejárásához. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátor használatával, mert ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvényeknek való átadásához argumentumként.
```cpp
class StringInfo : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| int [get_LengthInTextElements](./get_lengthintextelements/)() const | Lekéri a szövegelemek számát a [StringInfo](./) objektumban. |
| [String](../../system/string/) [get_String](./get_string/)() const | Lekéri a [StringInfo](./) objektum értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| int [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hashelését. |
| static [String](../../system/string/) [GetNextTextElement](./getnexttextelement/)(const [String](../../system/string/)\&) | Lekéri az adott karakterlánc első elemét. |
| static [String](../../system/string/) [GetNextTextElement](./getnexttextelement/)(const [String](../../system/string/)\&, int) | Lekéri a megadott indexű elemet a megadott karakterláncból. |
| static [SharedPtr](../../system/sharedptr/)\<[TextElementEnumerator](../textelementenumerator/)\> [GetTextElementEnumerator](./gettextelementenumerator/)(const [String](../../system/string/)\&) | Létrehoz egy enumerátort a karakterlánc karaktereinek bejárásához. |
| static [SharedPtr](../../system/sharedptr/)\<[TextElementEnumerator](../textelementenumerator/)\> [GetTextElementEnumerator](./gettextelementenumerator/)(const [String](../../system/string/)\&, int) | Létrehoz egy enumerátort a karakterlánc karaktereinek bejárásához a megadott indextől kezdve. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csupán új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [StringInfo](./)\& [operator=](./operator_equal/)(const [StringInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csupán új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static [ArrayPtr](../../system/arrayptr/)\<int\> [ParseCombiningCharacters](./parsecombiningcharacters/)(const [String](../../system/string/)\&) | Lekéri az alapkarakterek, magas szorzókarakterek és vezérlőkarakterek indexeit. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítás a value típusú objektum és a nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_String](./set_string/)(const [String](../../system/string/)\&) | Beállítja a [StringInfo](./) objektum értékét. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot **uint32_t** gyenge mutatóként (nem megosztottként) állítja. Lehetővé teszi, hogy a konténerekben a mutatókat gyenge módra cserélje. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [StringInfo](./stringinfo/)() | RTTI információ. |
|  [StringInfo](./stringinfo/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [StringInfo](./stringinfo/)(const [StringInfo](./)\&) |  |
| [String](../../system/string/) [SubstringByTextElements](./substringbytextelements/)(int) const | Lekéri a szövegelemek részletét a megadott szövegelemtől az utolsó szövegelemig. |
| [String](../../system/string/) [SubstringByTextElements](./substringbytextelements/)(int, int) const | Lekéri a szövegelemek részletét a megadott szövegelemtől a megadott számú szövegelemig. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)