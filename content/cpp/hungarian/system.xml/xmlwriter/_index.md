---
title: XmlWriter
second_title: Aspose.Slides C++ API referenciája
description: Egy olyan írót reprezentál, amely gyors, nem gyorsítótárazott, csak előrehaladó módon generál adatfolyamokat vagy fájlokat, amelyek XML adatot tartalmaznak.
type: docs
weight: 573
url: /hu/system.xml/xmlwriter/
---
## XmlWriter osztály

Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [Close](./close/)() | Ha egy származtatott osztályban felül van definiálva, lezárja ezt az adatfolyamot és az alatta lévő adatfolyamot. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Létrehoz egy új [XmlWriter](./) példányt a megadott fájlnév használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](./) példányt a fájlnév és a [XmlWriterSettings](../xmlwritersettings/) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Létrehoz egy új [XmlWriter](./) példányt a megadott adatfolyam használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](./) példányt az adatfolyam és a [XmlWriterSettings](../xmlwritersettings/) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Létrehoz egy új [XmlWriter](./) példányt a megadott TextWriter használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](./) példányt a TextWriter és a [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Létrehoz egy új [XmlWriter](./) példányt a megadott [Text::StringBuilder](../../system.text/stringbuilder/) használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](./) példányt a [Text::StringBuilder](../../system.text/stringbuilder/) és [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Létrehoz egy új [XmlWriter](./) példányt a megadott [XmlWriter](./) objektum használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Létrehoz egy új [XmlWriter](./) példányt a megadott [XmlWriter](./) és [XmlWriterSettings](../xmlwritersettings/) objektumok használatával. |
| void [Dispose](./dispose/)() override | Felszabadítja a [XmlWriter](./) osztály aktuális példánya által használt összes erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual void [Flush](./flush/)() | Ha egy származtatott osztályban felül van definiálva, kiüríti a pufferben lévő adatot az alatta lévő adatfolyamokra, és kiüríti az alatta lévő adatfolyamot is. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Visszaadja azt a [XmlWriterSettings](../xmlwritersettings/) objektumot, amelyet ennek a [XmlWriter](./) példánynak a létrehozásához használtak. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Ha egy származtatott osztályban felül van definiálva, lekéri az író állapotát. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Ha egy származtatott osztályban felül van definiálva, lekéri a jelenlegi **xml:lang** hatókört. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Ha egy származtatott osztályban felül van definiálva, lekéri az aktuális **xml:space** hatókört jelző XmlSpace objektumot. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, visszaadja a legközelebbi előtagot, amely a jelenlegi névtér hatókörben a névtér URI-hez van definiálva. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia módon hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóvá (ahelyett, hogy megosztott lenne) állítja. Lehetővé teszi a konténerekben lévő mutatók gyenge módra való váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ha egy származtatott osztályban felül van definiálva, kiírja az összes attribútumot, amely a [XmlReader](../xmlreader/) aktuális pozíciójában található. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, egy attribútumot ír a megadott helyi névvel, névtér-URI-val és értékkel. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja az attribútumot a megadott helyi névvel és értékkel. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja az attribútumot a megadott előtaggal, helyi névvel, névtér-URI-val és értékkel. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Ha egy származtatott osztályban felül van definiálva, a megadott bináris bájtokat Base64-ként kódolja, és kiírja a keletkezett szöveget. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Ha egy származtatott osztályban felül van definiálva, a megadott bináris bájtokat **BinHex**-ként kódolja, és kiírja a keletkezett szöveget. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, kiír egy **...** blokkot, amely a megadott szöveget tartalmazza. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Ha egy származtatott osztályban felül van definiálva, kikényszeríti egy karakter entitás generálását a megadott Unicode karakterértékhez. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Ha egy származtatott osztályban felül van definiálva, szöveget ír egy bufferből egyszerre. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, egy **** kommentet ír a megadott szöveggel. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a DOCTYPE deklarációt a megadott névvel és opcionális attribútumokkal. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott helyi névvel és értékkel. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott helyi névvel, névtér-URI-val és értékkel. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy elemet a megadott előtaggal, helyi névvel, névtér-URI-val és értékkel. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Ha egy származtatott osztályban felül van definiálva, bezárja az előző XmlWriter::WriteStartAttribute(String,String) hívást. |
| virtual void [WriteEndDocument](./writeenddocument/)() | Ha egy származtatott osztályban felül van definiálva, bezárja az összes nyitott elemet vagy attribútumot, és visszaállítja az írót a Start állapotba. |
| virtual void [WriteEndElement](./writeendelement/)() | Ha egy származtatott osztályban felül van definiálva, bezár egy elemet és levonja a hozzá tartozó névtér hatókört. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiír egy entitásreferenciát **&name**; formában. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Ha egy származtatott osztályban felül van definiálva, bezár egy elemet és levonja a hozzá tartozó névtér hatókört. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott nevet, biztosítva, hogy az a W3C XML 1.0 ajánlás ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) szerint érvényes legyen. |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott nevet, biztosítva, hogy az a W3C XML 1.0 ajánlás ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) szerint érvényes NmToken legyen. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Ha egy származtatott osztályban felül van definiálva, mindent átmásol a olvasóból a íróba, és az olvasót a következő testvér kezdetére mozgatja. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Átmásolja azXPathNavigator objektum összes tartalmát az íróba. Az XPathNavigator pozíciója változatlan marad. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, kiír egy feldolgozási instrukciót, amelyben a név és a szöveg között szerepel egy szóköz, a következő módon: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a névtérrel ellátott nevet. Ez a metódus megkeresi a megadott névtérhez tartozó, hatókörben lévő előtagot. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Ha egy származtatott osztályban felül van definiálva, kézzel nyers markup-ot ír ki egy karakterpufferből. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kézzel nyers markup-ot ír ki egy karakterláncból. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Kiír egy attribútum kezdő részét a megadott helyi névvel és névtér-URI-val. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja egy attribútum kezdő részét a megadott előtaggal, helyi névvel és névtér-URI-val. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Kiír egy attribútum kezdő részét a megadott helyi névvel. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Ha egy származtatott osztályban felül van definiálva, kiírja az XML nyilatkozatot a "1.0" verzióval. |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Ha egy származtatott osztályban felül van definiálva, kiírja az XML nyilatkozatot a "1.0" verzióval és a standalone attribútummal. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott kezdő tagot és hozzárendeli a megadott névtérhez. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott kezdő tagot és hozzárendeli a megadott névtérhez és előtaghoz. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiír egy kezdő tagot a megadott helyi névvel. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott szövegtartalmat. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Ha egy származtatott osztályban felül van definiálva, előállítja és kiírja a szurrogát karakter entitást a szurrogát pár számára. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Kiírja az objektum értékét. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Kiír egy [String](../../system/string/) értéket. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Kiír egy [Boolean](../../system/boolean/) értéket. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Kiír egy [DateTime](../../system/datetime/) értéket. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Kiír egy [DateTimeOffset](../../system/datetimeoffset/) értéket. |
| virtual void [WriteValue](./writevalue/)(**double**) | Kiír egy [Double](../../system/double/) értéket. |
| virtual void [WriteValue](./writevalue/)(**float**) | Kiír egy egyszeres pontosságú lebegőpontos számot. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Kiír egy [Decimal](../../system/decimal/) értéket. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Kiír egy [Int32](../../system/int32/) értéket. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Kiír egy [Int64](../../system/int64/) értéket. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, kiírja a megadott whitespace karaktert. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Az adott osztály egy példányára mutató megosztott mutató alias-a. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)