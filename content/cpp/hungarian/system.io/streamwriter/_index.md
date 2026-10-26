---
title: StreamWriter
second_title: Aspose.Slides C++ API-referencia
description: "Egy olyan írót képvisel, amely karaktereket ír egy bájt stream-be. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 391
url: /hu/system.io/streamwriter/
---
## StreamWriter osztály

Képvisel egy író objektumot, amely karaktereket ír egy bájt stream-be. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Close](./close/)() override | Bezárja a stream-et és felszabadítja a megszerzett erőforrásokat. |
| void [Dispose](./dispose/)() override | Felszabadítja az összes erőforrást, amelyet a jelenlegi objektum használ, és bezárja az alatta lévő stream-et. |
| virtual void [Dispose](./dispose/)(**bool**) | Felszabadítja az összes erőforrást, amelyet a jelenlegi objektum használ, és bezárja az alatta lévő stream-et. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| void [Flush](./flush/)() override | Kiüríti a puffer tartalmát az alatta lévő stream-be, majd kiüríti az alatta lévő stream-et. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Visszaad egy értéket, amely jelzi, hogy a [StreamWriter](./) minden alkalommal kiüríti-e az adatot az alatta lévő stream-be, amikor a [StreamWriter::Write](./write/) metódus meghívásra kerül. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Visszaad egy megosztott mutatót egy olyan objektumra, amely az alatta lévő stream-et képviseli. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Visszaadja a jelenleg használt kódolást. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Visszaad egy sort lezáró karakterláncot. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Visszaad egy sort lezáró karakterláncot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal társított referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsökkentőt a megadott értékkel. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Visszaad egy értéket, amely meghatározza, hogy a [StreamWriter](./) minden alkalommal kiüríti-e az adatot az alatta lévő stream-be, amikor a [StreamWriter::Write](./write/) metódus meghívásra kerül. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Beállít egy sort lezáró karakterláncot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a konténerekben lévő mutatók gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott alatta lévő stream-be ír karaktereket UTF-8 kódolással és 1024 bájt alapértelmezett méretű pufferral. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott alatta lévő stream-be ír karaktereket a megadott kódolással és 1024 bájt alapértelmezett méretű pufferral. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott alatta lévő stream-be ír karaktereket a megadott kódolással és a megadott méretű pufferral. Egy paraméter határozza meg, hogy az alatta lévő stream bezárásra kerüljön-e, amikor az [StreamWriter](./) objektum elvetésre kerül. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott fájlba ír karaktereket UTF-8 kódolással és 1024 bájt alapértelmezett méretű pufferral. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott fájlba ír karaktereket a megadott kódolással és 1024 bájt alapértelmezett méretű pufferral. Egy paraméter határozza meg, hogy az adat a fájlhoz legyen-e hozzáfűzve vagy felülírja a fájlt. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Az [StreamWriter](./) objektum egy példányát hozza létre, amely a megadott fájlba ír karaktereket a megadott kódolással és puffermérettel. Egy paraméter határozza meg, hogy az adat a fájlhoz legyen-e hozzáfűzve vagy felülírja a fájlt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(char_t) override | Megírja a megadott karaktert a stream-be. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Megírja a megadott karakterláncot a stream-be. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Megírja a megadott objektum string ábrázolását a stream-be. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Megírja az összes karaktert a megadott tömbből a stream-be. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Megírja a megadott karaktertömb UTF-16 karakterek megadott részhalmazát a stream-be. |
| void [Write](./write/)(const char_t *) override | Megírja a megadott C-karakterláncot a stream-be. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Megírja a megadott objektum string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**bool**) | Megírja a megadott logikai érték string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Megírja a megadott [Decimal](../../system/decimal/) objektum string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**double**) | Megírja a megadott double-pontos lebegőpontos érték string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(int) | Megírja a megadott 32 bites egész szám string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Megírja a megadott 64 bites egész szám string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**float**) | Megírja a megadott egyszeres pontosságú lebegőpontos érték string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Megírja a megadott 32 bites előjel nélküli egész szám string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Megírja a megadott 64 bites előjel nélküli egész szám string ábrázolását a stream-be. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Megírja a megadott [TypeInfo](../../system/typeinfo/) objektum string ábrázolását a stream-be. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Megírja a megadott értékeket a megadott formátumnak megfelelően a stream-be. |
| void [WriteLine](./writeline/)() override | Megírja a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Megírja a megadott karakterláncot, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Megírja a megadott objektum string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Megírja az összes karaktert a megadott tömbből, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Megírja a megadott karaktertömb UTF-16 karakterek megadott részhalmazát, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const char_t *) override | Megírja a megadott C-karakterláncot, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Megírja a megadott objektum string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Megírja a megadott logikai érték string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Megírja a megadott karaktert, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Megírja a megadott [Decimal](../../system/decimal/) objektum string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Megírja a megadott double-pontos lebegőpontos érték string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Megírja a megadott 32 bites egész szám string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Megírja a megadott 64 bites egész szám string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Megírja a megadott egyszeres pontosságú lebegőpontos érték string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Megírja a megadott 32 bites előjel nélküli egész szám string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Megírja a megadott 64 bites előjel nélküli egész szám string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Megírja a megadott [TypeInfo](../../system/typeinfo/) objektum string ábrázolását, majd a sort lezáró karaktereket a stream-be. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Megírja a megadott értékeket a megadott formátumnak megfelelően, majd a sort lezáró karaktereket a stream-be. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
|  [~StreamWriter](./~streamwriter/)() | Megsemmisítő. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Megsemmisítő. |

## Lásd még

* Osztály [TextWriter](../textwriter/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)