---
title: StreamReader
second_title: Aspose.Slides C++ API referenciája
description: "Egy olvasót képvisel, amely karaktereket olvas egy bájtos adatfolyamból. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákhoz és/vagy assert hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként funkcióknak való átadáskor."
type: docs
weight: 378
url: /hu/system.io/streamreader/
---
## StreamReader osztály

Egy olvasót képvisel, amely karaktereket olvas egy bájtos adatfolyamból. Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad példányosítani. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákhoz és/vagy assert hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként funkcióknak való átadáskor.

```cpp
class StreamReader : public System::IO::TextReader
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Close](./close/)() override | Bezárja az aktuális és az alatta lévő adatfolyamokat. |
| virtual void [Dispose](./dispose/)(**bool**) | Felszabadítja az aktuális objektum által használt összes erőforrást, és bezárja az alatta lévő adatfolyamot. |
| void [Dispose](./dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást, és bezárja az alatta lévő adatfolyamot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Visszaad egy megosztott mutatót egy olyan objektumra, amely az alatta lévő adatfolyamot képviseli. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Visszaadja a jelenleg használt kódolást. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Visszaad egy értéket, amely jelzi, hogy elérte-e az adatfolyam végét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum képvisel-e egy példányt a targetType által leírt típusból. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| int [Peek](./peek/)() override | Olvas egyetlen karaktert az adatfolyamból anélkül, hogy megváltoztatná az olvasási kurzort. |
| int [Read](./read/)() override | Olvas egyetlen karaktert az adatfolyamból. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Olvasza a megadott számú karaktert az adatfolyamból, UTF-16 kódolásra konvertálja, és a kapott UTF-16 karaktereket a megadott karaktertömbbe írja a megadott pozíciótól kezdve. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Olvasza a megadott maximális számú karaktert az aktuális szövegolvasóból, és a megadott indexnél kezdődően egy pufferbe írja az adatot. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Olvas karaktereket az adatfolyamból, amíg el nem éri az aktuális sor végét. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Olvas karaktereket az adatfolyamból, amíg el nem éri az adatfolyam végét. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (ahelyett, hogy megosztottra) állítja be. Lehetővé teszi a mutatók konténerekben való átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 1024 bájtos pufferrel. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 1024 bájtos pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 1024 bájtos pufferrel. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 1024 bájtos pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas a megadott kódolás használatával és a megadott méretű pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott fájlból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 4096 bájtos pufferrel. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott fájlból karaktereket olvas UTF-8 kódolás használatával és egy alapértelmezett 4096 bájtos pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott fájlból karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 4096 bájtos pufferrel. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott alatta lévő adatfolyamból karaktereket olvas a megadott kódolás használatával és egy alapértelmezett 4096 bájtos pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Létrehoz egy [StreamReader](./) objektum példányt, amely a megadott fájlból karaktereket olvas a megadott kódolás használatával és a megadott méretű pufferrel. Egy paraméter megadja, hogy a byte order mark detektálás legyen-e engedélyezve. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Elpusztítja az objektumot. Felszabadítja az összes belső adatstruktúrát. |
|  [~StreamReader](./~streamreader/)() | Dekonstruktor. |

## Lásd még

* Osztály [TextReader](../textreader/)
* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)