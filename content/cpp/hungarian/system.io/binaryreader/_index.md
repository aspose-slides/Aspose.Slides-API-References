---
title: BinaryReader
second_title: Aspose.Slides for C++ API referencia
description: "Egy olvasót reprezentál, amely primitív adattípusokat bináris adatokként olvas be egy adott kódolásban. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt a veremben vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 92
url: /hu/system.io/binaryreader/
---
## BinaryReader osztály


Ez egy olvasót reprezentál, amely primitív adattípusokat bináris adatokként olvas be egy adott kódolásban. Ennek az osztálynak a példányait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt a veremben vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához.

```cpp
class BinaryReader : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [BinaryReader](./) osztály egy példányát hozza létre, amely az adott adatfolyamból UTF-8 kódolással olvas adatot. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [BinaryReader](./) osztály egy példányát hozza létre, amely az adott adatfolyamból a megadott kódolással olvas adatot. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | [BinaryReader](./) osztály egy példányát hozza létre, amely az adott adatfolyamból a megadott kódolással olvas adatot. |
| virtual void [Close](./close/)() | Lezárja a jelenlegi [BinaryReader](./) objektumot és a mögöttes bemeneti adatfolyamot. |
| void [Dispose](./dispose/)() override | Felszabadítja a jelenlegi objektum által használt összes erőforrást és lezárja a mögöttes adatfolyamot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Visszaadja a bemeneti adatfolyamot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciacsounter adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasításban a zárolást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| virtual int [PeekChar](./peekchar/)() | Egyetlen karaktert olvas be a bemeneti adatfolyamból anélkül, hogy a folyam olvasási kurzorát módosítaná. |
| virtual int [Read](./read/)() | Egyetlen karaktert olvas be a bemeneti adatfolyamból. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | A megadott számú bájtot olvassa be a bemeneti adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | A megadott számú karaktert olvassa be a bemeneti adatfolyamból, UTF-16 kódolásra konvertálja, majd a kapott UTF-16 karaktereket a megadott karaktertömbbe írja a meghatározott pozíciótól kezdve. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Egyetlen bájtot olvas be a bemeneti adatfolyamból, és visszaadja annak logikai értékét. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Egyetlen bájtot olvas be a bemeneti adatfolyamból. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | A megadott számú bájtot olvassa be a bemeneti adatfolyamból. |
| virtual char_t [ReadChar](./readchar/)() | Egyetlen karaktert olvas be a bemeneti adatfolyamból. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | A megadott számú karaktert olvassa be a bemeneti adatfolyamból, és UTF-16 kódolásban adja vissza. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NINCS MEGVALÓSÍTVA. |
| virtual **double** [ReadDouble](./readdouble/)() | 8 bájtot olvas be a bemeneti adatfolyamból, és dupla pontosságú lebegőpontos értékként adja vissza. |
| virtual **int16_t** [ReadInt16](./readint16/)() | 2 bájtot olvas be a bemeneti adatfolyamból, és 16 bites egészként adja vissza. |
| virtual int [ReadInt32](./readint32/)() | 4 bájtot olvas be a bemeneti adatfolyamból, és 32 bites egészként adja vissza. |
| virtual **int64_t** [ReadInt64](./readint64/)() | 8 bájtot olvas be a bemeneti adatfolyamból, és 64 bites egészként adja vissza. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Egyetlen bájtot olvas be a bemeneti adatfolyamból, és előjeles 8 bites egészként adja vissza. |
| virtual **float** [ReadSingle](./readsingle/)() | 4 bájtot olvas be a bemeneti adatfolyamból, és egyszeres pontosságú lebegőpontos értékként adja vissza. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Olvas egy karakterláncot a jelenlegi adatfolyamból. A karakterlánc előtagként tartalmazza a hosszát, amelyet 7 bites egészekkel kódol. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | 2 bájtot olvas be a bemeneti adatfolyamból, és 16 bites előjel nélküli egészként adja vissza. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | 4 bájtot olvas be a bemeneti adatfolyamból, és 32 bites előjel nélküli egészként adja vissza. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | 8 bájtot olvas be a bemeneti adatfolyamból, és 64 bites előjel nélküli egészként adja vissza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (nem megosztottként). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~BinaryReader](./~binaryreader/)() | Megsemmisítő. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)