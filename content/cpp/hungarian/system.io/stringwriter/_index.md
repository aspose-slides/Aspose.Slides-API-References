---
title: StringWriter
second_title: Aspose.Slides C++ API Referencia
description: "Egy TextWriter-t valósít meg, amely információkat ír egy karakterláncba. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő átadásra a függvényeknek."
type: docs
weight: 417
url: /hu/system.io/stringwriter/
---
## StringWriter osztály

Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Lezárja az adatfolyamot és felszabadítja a megszerzett erőforrásokat. |
| void [Dispose](../textwriter/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és lezárja az alatta lévő adatfolyamot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C#-stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C#-stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN semmilyen értékkel, így a NaN-nal sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN semmilyen értékkel, így a NaN-nal sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual void [Flush](../textwriter/flush/)() | Kiüríti a puffer tartalmát az alatta lévő adatfolyamra. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Visszaadja a jelenleg használt kódolást. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Visszaadja a jelenleg használt [IFormatProvider](../../system/iformatprovider/) objektumot. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Visszaad egy sorvége karakterláncot. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Visszaad egy sorvége karakterláncot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Visszaadja a jelenleg használt StringBuilder-t. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzés, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Beállítja a sorvége karakterláncot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti a megosztott referenciaszámlálót és visszaadja azt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Új példányt hoz létre a [StringWriter](./)-ből a megadott StringBuilder és [IFormatProvider](../../system/iformatprovider/) használatával. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Új példányt hoz létre a [StringWriter](./)-ből a megadott StringBuilder és a jelenlegi kultúrából származó [IFormatProvider](../../system/iformatprovider/) használatával. |
| [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Új példányt hoz létre a [StringWriter](./)-ból a megadott [IFormatProvider](../../system/iformatprovider/) használatával. |
| [StringWriter](./stringwriter/)() | Új példányt hoz létre a [StringWriter](./)-ból a jelenlegi kultúrából származó [IFormatProvider](../../system/iformatprovider/) használatával. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaadja az alapsztringet. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(char_t) override | A megadott karaktert írja az adatfolyamba. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | A megadott karaktertömbből a megadott karaktertartományt írja az adatfolyamba. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | A megadott stringet írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | A megadott objektum string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**bool**) | A megadott logikai érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | A megadott [Decimal](../../system/decimal/) objektum string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**double**) | A megadott dupla pontosságú lebegőpontos érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(int) | A megadott 32 bites egész érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | A megadott 64 bites egész érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**float**) | A megadott egyszeres pontosságú lebegőpontos érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | A megadott előjel nélküli 32 bites egész érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | A megadott előjel nélküli 64 bites egész érték string ábrázolását írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Az adott tömb összes karakterét írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(const char_t *) | A megadott c-stringet írja az adatfolyamba. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | A megadott [TypeInfo](../../system/typeinfo/) objektum string ábrázolását írja az adatfolyamba. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | A megadott értékeket a megadott formátum szerint formázva írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)() | A sorvége karaktereket írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | A megadott objektum string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | A megadott logikai érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | A megadott karaktert a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | A megadott [Decimal](../../system/decimal/) objektum string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | A megadott dupla pontosságú lebegőpontos érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | A megadott 32 bites egész érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | A megadott 64 bites egész érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | A megadott egyszeres pontosságú lebegőpontos érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | A megadott stringet a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | A megadott előjel nélküli 32 bites egész érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | A megadott előjel nélküli 64 bites egész érték string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Az adott tömb összes karakterét a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | A megadott karaktertömbből a megadott UTF-16 tartományt a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | A megadott c-stringet a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | A megadott [TypeInfo](../../system/typeinfo/) objektum string ábrázolását a sorvégi karakterekkel együtt írja az adatfolyamba. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | A megadott értékeket a megadott formátum szerint formázva, a sorvégi karakterekkel együtt írja az adatfolyamba. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destruktor. |

## Lásd még

* Osztály [TextWriter](../textwriter/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)