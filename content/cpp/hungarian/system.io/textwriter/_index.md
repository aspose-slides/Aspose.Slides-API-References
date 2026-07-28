---
title: TextWriter
second_title: Aspose.Slides C++ API referencia
description: "Egy alaposztály azoknak az osztályoknak, amelyek írókat képviselnek, és karakter sorozatokat írnak különböző célhelyekre. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozza létre ennek a típusnak a példányát a stacken vagy az operator new-vel, mert futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra."
type: docs
weight: 443
url: /hu/system.io/textwriter/
---
## TextWriter osztály


Alap osztály azoknak az osztályoknak, amelyek írókat képviselnek, amelyek karakter sorozatokat írnak különböző célhelyekre. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási sérüléseket eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra.

```cpp
class TextWriter : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Close](./close/)() | Lezárja a stream-et és felszabadítja a megszerzett erőforrásokat. |
| void [Dispose](./dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és lezárja az alatta lévő stream-et. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual void [Flush](./flush/)() | Kiüríti a puffer tartalmát az alatta lévő stream-be. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Visszaadja a jelenleg használt kódolást. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Visszaad egy sortörő karakterláncot. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Visszaad egy sortörő karakterláncot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Beállít egy sortörő karakterláncot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókban történő gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Kiírja a megadott objektum karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(**bool**) | Kiírja a megadott logikai érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(char_t) | Kiírja a megadott karaktert a stream-be. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Kiírja a megadott [Decimal](../../system/decimal/) objektum karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(**double**) | Kiírja a megadott dupla pontosságú lebegőpontos érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(int) | Kiírja a megadott 32 bites egész érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(**int64_t**) | Kiírja a megadott 64 bites egész érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(**float**) | Kiírja a megadott egyszeres pontosságú lebegőpontos érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Kiírja a megadott karakterláncot a stream-be. |
| virtual void [Write](./write/)(**uint32_t**) | Kiírja a megadott előjel nélküli 32 bites egész érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(**uint64_t**) | Kiírja a megadott előjel nélküli 64 bites egész érték karakterlánc reprezentációját a stream-be. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Kiírja a megadott tömb összes karakterét a stream-be. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Kiírja a megadott karaktertömbből a megadott részletet (UTF-16 karakterek) a stream-be. |
| virtual void [Write](./write/)(const char_t *) | Kiírja a megadott C-stringet a stream-be. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Kiírja a megadott [TypeInfo](../../system/typeinfo/) objektum karakterlánc reprezentációját a stream-be. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Kiírja a megadott értékeket a megadott formátum szerint a stream-be. |
| virtual void [WriteLine](./writeline/)() | Kiírja a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Kiírja a megadott objektum karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**bool**) | Kiírja a megadott logikai érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(char_t) | Kiírja a megadott karaktert, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Kiírja a megadott [Decimal](../../system/decimal/) objektum karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**double**) | Kiírja a megadott dupla pontosságú lebegőpontos érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(int) | Kiírja a megadott 32 bites egész érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Kiírja a megadott 64 bites egész érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**float**) | Kiírja a megadott egyszeres pontosságú lebegőpontos érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Kiírja a megadott karakterláncot, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Kiírja a megadott előjel nélküli 32 bites egész érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Kiírja a megadott előjel nélküli 64 bites egész érték karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Kiírja a megadott tömb összes karakterét, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Kiírja a megadott karaktertömbből a megadott részletet (UTF-16 karakterek), majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Kiírja a megadott C-stringet, majd a sortörő karaktereket a stream-be. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Kiírja a megadott [TypeInfo](../../system/typeinfo/) objektum karakterlánc reprezentációját, majd a sortörő karaktereket a stream-be. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Kiírja a megadott értékeket a megadott formátum szerint, majd a sortörő karaktereket a stream-be. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~TextWriter](./~textwriter/)() | Destruktor. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóhoz ehhez az osztályhoz. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)