---
title: XmlWriterSettings
second_title: Aspose.Slides C++ API hivatkozás
description: "Megadja az XmlWriter::Create metódus által létrehozott XmlWriter objektumon támogatandó funkciók halmazát."
type: docs
weight: 586
url: /hu/system.xml/xmlwritersettings/
---
## XmlWriterSettings osztály


Megadja a [XmlWriter](../xmlwriter/) objektumon támogatandó funkciók halmazát, amelyet a [XmlWriter::Create](../xmlwriter/create/) metódus hoz létre.

```cpp
class XmlWriterSettings : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Létrehoz egy másolatot a [XmlWriterSettings](./) példányról. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlít objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Visszaad egy értéket, amely jelzi, hogy az XML író ellenőrizze-e, hogy a dokumentum összes karaktere megfelel-e a W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) "2.2 Characters" szakaszának. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) is lezárja-e a kapcsolódó stream-et vagy TextWriter-t, amikor a [XmlWriter::Close](../xmlwriter/close/) metódus meghívásra kerül. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Visszaadja azt a megfelelőségi szintet, amelyet az XML író az XML kimenet ellenőrzésekor figyelembe vesz. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) nem escapeli az URI attribútumokat. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Visszaadja a használandó szövegkódolás típusát. |
| **bool** [get_Indent](./get_indent/)() | Visszaad egy értéket, amely jelzi, hogy be kell-e húzni az elemeket. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Visszaadja a behúzásnál használandó karakterláncot. Ez a beállítás akkor kerül alkalmazásra, amikor a [XmlWriterSettings::set_Indent](./set_indent/) értéke **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) eltávolítsa-e a duplikált névtérek deklarációit XML tartalom írása közben. Alapértelmezés szerint az író az összes, a névtér feloldóban jelen lévő névtérdeklarációt kiírja. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Visszaadja a sortöréshez használandó karakterláncot. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Visszaad egy értéket, amely jelzi, hogy normalizálni kell-e a sortöréseket a kimenetben. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Visszaad egy értéket, amely jelzi, hogy az attribútumok újsorban legyenek-e kiírva. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Visszaad egy értéket, amely jelzi, hogy kihagyható-e az XML deklaráció. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Visszaadja a [XmlWriter](../xmlwriter/) kimenet sorosításához használt módszert. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) hozzáadja-e a záró címkéket minden nyitott elemcímkéhez, amikor a [XmlWriter::Close](../xmlwriter/close/) metódus meghívásra kerül. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlít értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [Reset](./reset/)() | Visszaállítja a beállítások osztály tagjait az alapértelmezett értékekre. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Beállít egy értéket, amely jelzi, hogy az XML író ellenőrizze-e, hogy a dokumentum összes karaktere megfelel-e a W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) "2.2 Characters" szakaszának. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) is lezárja-e a kapcsolódó stream-et vagy TextWriter-t, amikor a [XmlWriter::Close](../xmlwriter/close/) metódus meghívásra kerül. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Beállítja azt a megfelelőségi szintet, amelyet az XML író az XML kimenet ellenőrzésekor figyelembe vesz. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) nem escapeli az URI attribútumokat. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Beállítja a használandó szövegkódolás típusát. |
| void [set_Indent](./set_indent/)(**bool**) | Beállít egy értéket, amely jelzi, hogy be kell-e húzni az elemeket. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Beállítja a behúzáskor használandó karakterláncot. Ez a beállítás akkor kerül alkalmazásra, amikor a [XmlWriterSettings::set_Indent](./set_indent/) értéke **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Beállít egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) eltávolítsa-e a duplikált névtérdeklarációkat XML tartalom írása közben. Alapértelmezés szerint az író az összes, a névtér feloldóban jelen lévő névtérdeklarációt kiírja. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Beállítja a sortöréshez használandó karakterláncot. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Beállít egy értéket, amely jelzi, hogy normalizálni kell-e a sortöréseket a kimenetben. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Beállít egy értéket, amely jelzi, hogy az attribútumok új sorban legyenek-e kiírva. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Beállít egy értéket, amely jelzi, hogy kihagyható-e az XML deklaráció. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a [XmlWriter](../xmlwriter/) hozzáadja-e a záró címkéket minden nyitott elemcímkéhez, amikor a [XmlWriter::Close](../xmlwriter/close/) metódus meghívásra kerül. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Inicializál egy új példányt a [XmlWriterSettings](./) osztályból. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott mutatóra, amely ennek az osztálynak egy példányára mutat. |

## Megjegyzések

Ennek az osztálynak csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad példányosítani. Soha ne hozzon létre példányokat ezen típusú objektumokból veremben vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy assert hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)