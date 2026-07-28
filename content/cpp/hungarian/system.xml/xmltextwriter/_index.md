---
title: XmlTextWriter
second_title: Aspose.Slides C++ API-referencia
description: Egy olyan írót képvisel, amely gyors, nem gyorsítótárazott, csak előre haladó módon generál adatfolyamokat vagy fájlokat, amelyek XML adatot tartalmaznak, és megfelelnek a W3C Extensible Markup Language (XML) 1.0 és a Namespaces in XML ajánlásoknak.
type: docs
weight: 521
url: /hu/system.xml/xmltextwriter/
---
## XmlTextWriter osztály

Egy olyan írót képvisel, amely gyors, nem gyorsítótárazott, csak előre haladó módon generál adatfolyamokat vagy fájlokat, amelyek XML adatot tartalmaznak, amely megfelel a W3C Extensible Markup Language (XML) 1.0 és a Namespaces in XML ajánlásoknak.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Close](./close/)() override | Bezárja ezt a folyamot és az alatta lévő folyamot. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott fájlnév használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a fájlnév és a [XmlWriterSettings](../xmlwritersettings/) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott adatfolyam használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt az adatfolyam és a [XmlWriterSettings](../xmlwritersettings/) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott TextWriter használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a TextWriter és a [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott [Text::StringBuilder](../../system.text/stringbuilder/) használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a [Text::StringBuilder](../../system.text/stringbuilder/) és a [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott [XmlWriter](../xmlwriter/) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](../xmlwriter/) példányt a megadott [XmlWriter](../xmlwriter/) és [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| void [Dispose](../xmlwriter/dispose/)() override | Felszabadítja az aktuális [XmlWriter](../xmlwriter/) osztály példány által használt összes erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [Flush](./flush/)() override | Kiüríti a pufferben lévő adatot az alatta lévő adatfolyamokra, és kiüríti az alábbi adatfolyamot is. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Visszaadja az alatta lévő adatfolyam objektumot. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Megmutatja, hogyan formázott a kimenet. |
| **int32_t** [get_Indentation](./get_indentation/)() | Visszaadja, hány IndentChars karaktert kell írni minden hierarchiaszinten, amikor [XmlTextWriter::set_Formatting](./set_formatting/) értéke [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Visszaadja, melyik karaktert kell használni a behúzáshoz, amikor [XmlTextWriter::set_Formatting](./set_formatting/) értéke [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Visszaad egy értéket, amely jelzi, hogy engedélyezett-e a névtér támogatás. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Visszaadja, melyik karaktert kell használni az attribútumértékek idézőjelezéséhez. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Visszaadja a [XmlWriterSettings](../xmlwritersettings/) objektumot, amelyet ennek a [XmlWriter](../xmlwriter/) példánynak a létrehozásához használtak. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Visszaadja az író állapotát. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Visszaadja a jelenlegi **xml:lang** hatókört. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Visszaad egy XmlSpace objektumot, amely a jelenlegi **xml:space** hatókört képviseli. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példánya-e a targetType által leírt típusnak. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Visszaadja a legközelebbi előtagot, amely a jelenlegi névtér hatókörben van definiálva a névtér URI-hez. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az érték típusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Megmutatja, hogyan formázott a kimenet. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Beállítja, hány IndentChars karaktert írjon minden szinthez a hierarchiában, amikor [XmlTextWriter::set_Formatting](./set_formatting/) értéke [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Beállítja, melyik karaktert használja a behúzáshoz, amikor [XmlTextWriter::set_Formatting](./set_formatting/) értéke [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Beállít egy értéket, amely jelzi, hogy engedélyezett-e a névtér támogatás. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Beállítja, melyik karaktert használja az attribútumértékek idézőjelezéséhez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonparamétert gyenge mutatóként állítja be (nem megosztott). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ha egy származtatott osztályban felül van definiálva, kiírja az összes attribútumot, amely a jelenlegi pozícióban található a [XmlReader](../xmlreader/)-ben. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, egy attribútumot ír ki a megadott helyi névvel, névtér URI-vel és értékkel. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja az attribútumot a megadott helyi névvel és értékkel. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja az attribútumot a megadott előtaggal, helyi névvel, névtér URI-val és értékkel. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | A megadott bináris bájtokat base64-kódba alakítja, és kiírja a keletkezett szöveget. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | A megadott bináris bájtokat binhex-kódba alakítja, és kiírja a keletkezett szöveget. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Kiír egy **...** blokkot, amely a megadott szöveget tartalmazza. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Kényszeríti egy karakter entitás generálását a megadott Unicode karakterértékhez. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Szöveget ír ki egy puffertől a másikig. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Kiír egy **** megjegyzést, amely a megadott szöveget tartalmazza. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Kiírja a DOCTYPE deklarációt a megadott névvel és opcionális attribútumokkal. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott helyi névvel és értékkel. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott helyi névvel, névtér URI-val és értékkel. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott előtaggal, helyi névvel, névtér URI-val és értékkel. |
| void [WriteEndAttribute](./writeendattribute/)() override | Bezárja az előző [XmlTextWriter::WriteStartAttribute](./writestartattribute/) hívást. |
| void [WriteEndDocument](./writeenddocument/)() override | Bezárja az összes nyitott elemet vagy attribútumot, és visszaállítja az írót a Start állapotba. |
| void [WriteEndElement](./writeendelement/)() override | Bezár egy elemet és visszalép a megfelelő névtér hatókörből. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Kiír egy entitásreferenciát **&name** formában. |
| void [WriteFullEndElement](./writefullendelement/)() override | Bezár egy elemet és visszalép a megfelelő névtér hatókörből. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Kiírja a megadott nevet, biztosítva, hogy az érvényes név legyen a [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) szerint. |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Kiírja a megadott nevet, biztosítva, hogy az érvényes **NmToken** legyen a [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) szerint. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ha egy származtatott osztályban felül van definiálva, mindent átmásol a olvasóból az íróba, és a olvasót a következő testvér kezdőpontjába mozgatja. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Mindent átmásol az XPathNavigator objektumból az íróba. Az XPathNavigator pozícája változatlan marad. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Kiír egy feldolgozási utasítást, ahol a név és a szöveg között szóköz van, a következőképpen: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Kiírja a névtérrel ellátott nevet. Ez a metódus lekéri az adott névtérhez tartozó előtagot a hatókörben. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Nyers markupot ír kézzel egy karakterpufferből. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Nyers markupot ír kézzel egy karakterláncból. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Kiír egy attribútum kezdő részét. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy attribútum kezdő részét a megadott helyi névvel és névtér URI-val. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Kiír egy attribútum kezdő részét a megadott helyi névvel. |
| void [WriteStartDocument](./writestartdocument/)() override | Kiírja az XML deklarációt a "1.0" verzióval. |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Kiírja az XML deklarációt a "1.0" verzióval és a standalone attribútummal. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Kiírja a megadott kezdőcímkét, és összekapcsolja a megadott névtérrel és előtaggal. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott kezdőcímkét, és összekapcsolja a megadott névtérrel. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiír egy kezdőcímkét a megadott helyi névvel. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Kiírja a megadott szövegtartalmat. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Generálja és kiírja a szurrogát karakter entitást a szurrogát karakterpárhoz. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Kiírja az objektum értékét. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Kiír egy [String](../../system/string/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Kiír egy [Boolean](../../system/boolean/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Kiír egy [DateTime](../../system/datetime/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Kiír egy [DateTimeOffset](../../system/datetimeoffset/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Kiír egy [Double](../../system/double/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Kiír egy egyszeres pontosságú lebegőpontos számot. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Kiír egy [Decimal](../../system/decimal/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Kiír egy [Int32](../../system/int32/) értéket. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Kiír egy [Int64](../../system/int64/) értéket. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Kiírja a megadott fehér karaktert. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Létrehoz egy példányt a [XmlTextWriter](./) osztályból a megadott adatfolyam és kódolás használatával. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Létrehoz egy példányt a [XmlTextWriter](./) osztályból a megadott fájl használatával. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Létrehoz egy példányt a [XmlTextWriter](./) osztályból a megadott TextWriter használatával. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a megosztott pointerhez, amely ennek az osztálynak egy példányára mutat. |

## Megjegyzések

Ajánlott a [XmlWriter](../xmlwriter/) osztályt használni helyette.

Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozza létre ennek a típusnak példányait stacken vagy a new operátorral, mert futásidejű hibákat és/vagy állításhibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert, hogy argumentumként átadja a függvényeknek.

## Lásd még

* osztály [XmlWriter](../xmlwriter/)
* névtér [System::Xml](../)
* könyvtár [Aspose.Slides](../../)