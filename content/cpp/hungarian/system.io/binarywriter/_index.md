---
title: BinaryWriter
second_title: Aspose.Slides C++ API Referenciája
description: "Egy olyan írót képvisel, amely primitív típusú értékeket ír egy bájt adatfolyamba. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 105
url: /hu/system.io/binarywriter/
---
## BinaryWriter osztály


Egy író objektumot képvisel, amely primitív típusú értékeket ír egy bájt adatfolyamba. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy a new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Létrehozza a [BinaryWriter](./) osztály egy példányát, amely a megadott kódolással a megadott adatfolyamra írja az adatokat. |
| void [Close](./close/)() | Lezárja a jelenlegi [BinaryWriter](./) objektumot és az alatta lévő kimeneti adatfolyamot. |
| void [Dispose](./dispose/)() override | Felszabadítja a jelenlegi objektum által használt összes erőforrást és lezárja az alatta lévő adatfolyamot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantikájával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [Flush](./flush/)() | Kiüríti a kimeneti adatfolyamot. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Visszaadja a kimeneti adatfolyamot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védelmi objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Beállítja a jelenlegi objektum által reprezentált adatfolyam pozícióját. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben történő gyenge módra állítását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védelmi objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [Write](./write/)(**uint8_t**) | Kiírja a megadott **uint8_t** értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Kiírja a megadott bájt tömbből a megadott részhalmazt a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Kiírja a megadott karaktertömbből a megadott részhalmaz UTF-16 karaktereket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**bool**) | Kiír egyetlen bájtot, amelynek értéke 0, ha **value** 'true', és 1, ha **value** 'false' a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(char16_t) | Kiírja a megadott 16 bites széles karakter értékét a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**int16_t**) | Kiírja a megadott 16 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(int) | Kiírja a megadott 32 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**int64_t**) | Kiírja a megadott 64 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**uint16_t**) | Kiírja a megadott előjel nélküli 16 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**uint32_t**) | Kiírja a megadott előjel nélküli 32 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**uint64_t**) | Kiírja a megadott előjel nélküli 64 bites egész értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**float**) | Kiírja a megadott egyszeres pontosságú lebegőpontos értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(**double**) | Kiírja a megadott dupla pontosságú lebegőpontos értéket a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Kiírja a megadott [Decimal](../../system/decimal/) érték bájt ábrázolását a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Kiír egy hossz előtaggal ellátott karakterláncot a jelenlegi kódolásban a kimeneti adatfolyamba. |
| virtual void [Write](./write/)(const char_t *) | Kiír egy hossz előtaggal ellátott karakterláncot a jelenlegi kódolásban a kimeneti adatfolyamba. |
|  [~BinaryWriter](./~binarywriter/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)