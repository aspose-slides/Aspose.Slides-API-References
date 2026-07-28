---
title: ConsoleOutput
second_title: Aspose.Slides C++ API Referencia
description: "A szabványos kimeneti adatfolyamot képviseli. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 209
url: /hu/system/consoleoutput/
---
## ConsoleOutput osztály

Képviseli a szabványos kimeneti adatfolyamot. Ennek az osztálynak a példányait csak a [System::MakeObject()](../makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy a new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Lezárja az adatfolyamot, és felszabadítja a szerzett erőforrásokat. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást, és lezárja az alatta lévő adatfolyamot. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Kiüríti a puffer tartalmát az alatta lévő adatfolyamra. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Mindig ASCII kódolást ad vissza. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Visszaadja a jelenleg használt [IFormatProvider](../iformatprovider/) objektumot. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Visszaadja a jelenleg használt [IFormatProvider](../iformatprovider/) objektumot. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Visszaad egy sorvége karakterláncot. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Visszaad egy sorvége karakterláncot. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | A C# [Object.GetHashCode()](../object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógja. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másoló konstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Beállít egy sorvége karakterláncot. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerben való gyenge módra való átkapcsolását. |
| int [SharedCount](../object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | A C# [Object.ToString()](../object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) konstrukciót. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(**bool**) override | Kiírja a megadott bool érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Kiírja a megadott objektum karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(char_t) override | Kiírja a megadott karakter értéket a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)([Decimal](../decimal/)) override | Kiírja a [Decimal](../decimal/) érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**double**) override | Kiírja a dupla pontosságú lebegőpontos érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**int32_t**) override | Kiírja a 32-bit egész érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**int64_t**) override | Kiírja a 64-bit egész érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**float**) override | Kiírja az egyetlen pontosságú lebegőpontos érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const [String](../string/)\&) override | Kiírja a megadott karakterlánc objektumot a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**uint32_t**) override | Kiírja a 32-bit előjel nélküli egész érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(**uint64_t**) override | Kiírja a 64-bit előjel nélküli egész érték karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Kiírja a megadott karaktertömb karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Kiírja a megadott karaktertömb egy értéktartományának karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const char_t *) override | Kiírja a megadott C-stringet a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Kiírja a megadott [TypeInfo](../typeinfo/) objektum karakterlánc ábrázolását a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Kiírja a megadott 32-bit egész érték karakterlánc ábrázolását az adatfolyamra. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Kiírja a megadott értékeket a megadott formátumnak megfelelően az adatfolyamra. |
| void [WriteLine](./writeline/)() override | Kiírja a jelenlegi sorvége karaktert a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Kiírja a megadott objektum karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**bool**) override | Kiírja a megadott bool érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(char_t) override | Kiírja a megadott karakter értéket, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Kiírja a [Decimal](../decimal/) érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**double**) override | Kiírja a dupla pontosságú lebegőpontos érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(int) override | Kiírja a 32-bit egész érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**int64_t**) override | Kiírja a 64-bit egész érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**float**) override | Kiírja az egyetlen pontosságú lebegőpontos érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Kiírja a megadott karakterlánc objektumot, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Kiírja az előjel nélküli 32-bit egész érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Kiírja az előjel nélküli 64-bit egész érték karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Kiírja a megadott karaktertömb karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Kiírja a megadott karaktertömb egy értéktartományának karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const char_t *) override | Kiírja a megadott C-stringet, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Kiírja a megadott [TypeInfo](../typeinfo/) objektum karakterlánc ábrázolását, majd a jelenlegi sorvéget a jelenlegi objektum által képviselt kimeneti adatfolyamra. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Kiírja a megadott értékeket a megadott formátumnak megfelelően, majd a sorvégi karaktereket az adatfolyamra. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |

## Lásd még

* Osztály [TextWriter](../../system.io/textwriter/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)