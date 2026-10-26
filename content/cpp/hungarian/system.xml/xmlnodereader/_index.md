---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API Referenciája
description: Egy olvasót reprezentál, amely gyors, nem gyorsítótárazott, csak előre irányuló hozzáférést biztosít az XmlNode-ban található XML adatokhoz.
type: docs
weight: 365
url: /hu/system.xml/xmlnodereader/
---
## XmlNodeReader osztály

Egy olvasót képvisel, amely gyors, nem gyorsítótárazott, csak előre irányuló hozzáférést biztosít az XML adatokhoz egy [XmlNode](../xmlnode/)-ben.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [Close](./close/)() override | Módosítja a [XmlNodeReader::get_ReadState](./get_readstate/)-t [ReadState::Closed](../readstate/)-ra. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott URI-val. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott URI, beállítások és a feldolgozáshoz szükséges kontextusinformáció használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott adatfolyam alapértelmezett beállításokkal. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott adatfolyam és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, alap URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, beállítások és a feldolgozáshoz szükséges kontextusinformáció használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és alap URI használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és a feldolgozáshoz szükséges kontextusinformáció használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Létrehozza az új [XmlReader](../xmlreader/) példányt a megadott XML olvasó és beállítások használatával. |
| void [Dispose](../xmlreader/dispose/)() override | Felszabadítja a [XmlReader](../xmlreader/) osztály jelenlegi példánya által használt összes erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra szolgál. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Visszaadja az aktuális csomóponton lévő attribútumok számát. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Visszaadja az aktuális csomópont alap URI-ját. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Visszaad egy értéket, amely azt jelzi, hogy a [XmlNodeReader](./) implementálja-e a bináris tartalom olvasó metódusait. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Visszaad egy értéket, amely azt jelzi, hogy a [XmlReader](../xmlreader/) implementálja-e a [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) metódust. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Visszaad egy értéket, amely azt jelzi, hogy ez az olvasó képes-e entitások feldolgozására és feloldására. |
| **int32_t** [get_Depth](./get_depth/)() override | Visszaadja az aktuális csomópont mélységét az XML dokumentumban. |
| **bool** [get_EOF](./get_eof/)() override | Visszaad egy értéket, amely azt jelzi, hogy az olvasó a stream végén áll-e. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Visszaad egy értéket, amely azt jelzi, hogy az aktuális csomópontnak vannak-e attribútumai. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Visszaad egy értéket, amely azt jelzi, hogy az aktuális csomópont rendelkezhet-e [XmlNodeReader::get_Value](./get_value/) értékkel. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Visszaad egy értéket, amely azt jelzi, hogy az aktuális csomópont egy olyan attribútum-e, amely a DTD vagy séma alapértelmezett értékéből lett generálva. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Visszaad egy értéket, amely azt jelzi, hogy az aktuális csomópont egy üres elem-e (például **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Visszaadja az aktuális csomópont helyi nevét. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaadja az aktuális csomópont kvalifikált nevét. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Visszaadja a csomópont névtér-URI-ját (ahogy azt a W3C Namespace specifikáció határozza meg), amelyen az olvasó áll. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Visszaadja a [XmlNameTable](../xmlnametable/) értéket, amely ehhez a megvalósításhoz tartozik. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Visszaadja az aktuális csomópont típusát. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Visszaadja az aktuális csomóponthoz tartozó névtér előtagot. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Ha egy származtatott osztályban felül van definiálva, visszaadja az attribútum értékét körülvevő idézőjel karaktert. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Visszaadja az olvasó állapotát. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Visszaadja a jelenlegi csomópontra rendelt séma információt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Visszaadja azt a [XmlReaderSettings](../xmlreadersettings/) objektumot, amelyet ennek a [XmlReader](../xmlreader/) példánynak a létrehozásához használtak. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Visszaadja az aktuális csomópont szöveges értékét. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Visszaadja az aktuális csomópont típusát. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Visszaadja az aktuális **xml:lang** hatókört. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Visszaadja az aktuális **xml:space** hatókört. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Visszaadja a megadott névű attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Visszaadja a megadott helyi névvel és névtér-URI-val rendelkező attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Visszaadja a megadott indexű attribútum értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Ha egy származtatott osztályban felül van definiálva, visszaadja a megadott indexű attribútum értékét. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, visszaadja a megadott [XmlReader::get_Name](../xmlreader/get_name/) értékű attribútumot. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, visszaadja a megadott [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékű attribútumot. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely azt jelzi, hogy a karakterlánc argumentum érvényes XML-név-e. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely azt jelzi, hogy a karakterlánc argumentum érvényes XML névtoken-e. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/) metódust, és ellenőrzi, hogy a jelenlegi tartalmi csomópont kezdő címke vagy üres elem címke-e. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/) metódust, és ellenőrzi, hogy a jelenlegi tartalmi csomópont kezdő címke vagy üres elem címke-e, valamint hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott argumentummal. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/) metódust, és ellenőrzi, hogy a jelenlegi tartalmi csomópont kezdő címke vagy üres elem címke-e, valamint hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Feloldja a névtér előtagot az aktuális elem hatókörében. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Áthelyezi a megadott névű attribútumra. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Áthelyezi a megadott helyi névvel és névtér-URI-val rendelkező attribútumra. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Áthelyezi a megadott indexű attribútumra. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ellenőrzi, hogy az aktuális csomópont tartalmi (nem fehérhely karaktert tartalmazó szöveg, **CDATA**, **Element**, **EndElement**, **EntityReference** vagy **EndEntity**) csomópont-e. Ha nem tartalmi csomópont, az olvasó a következő tartalmi csomópontra vagy a fájl végére ugrik. Kihagyja a következő típusú csomópontokat: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, vagy **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Áthelyezi az elemet, amely a jelenlegi attribútumcsomópontot tartalmazza. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Áthelyezi az első attribútumra. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Áthelyezi a következő attribútumra. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másolókonstruktor. Nem másol semmit, valójában csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Nem másol semmit, valójában csak inicializálja az új objektumot és lehetőve teszi a másolás nélküli konstrukciót. |
| **bool** [Read](./read/)() override | Beolvassa a következő csomópontot a streamből. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Feldolgozza az attribútum értékét egy vagy több **[Text](../../system.text/)**, **EntityReference** vagy **EndEntity** csomóppá. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | A megadott típusú objektumként olvassa be a tartalmat. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat és visszaadja a Base64 dekódolt bináris bájtokat. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat és visszaadja a BinHex dekódolt bináris bájtokat. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál [Boolean](../../system/boolean/)-ként. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál [DateTimeOffset](../../system/datetimeoffset/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál [Decimal](../../system/decimal/) objektként. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál egyszeres pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál 32 bites előjeles egész számként. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Beolvassa a szöveges tartalgot a jelenlegi pozíciónál 64 bites előjeles egész számként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Beolvassa a szöveges tartalmat a jelenlegi pozíciónál [Object](../../system/object/)-ként. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [String](../../system/string/) objektumként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Beolvassa az elem tartalmát a kért típusban. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az elem tartalmát a kért típusban. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet és dekódolja a Base64 tartalmat. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet és dekódolja a BinHex tartalmat. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat egyes pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat egyes pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat 32 bites előjeles egész számként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat 32 bites előjeles egész számként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat 64 bites előjeles egész számként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat 64 bites előjeles egész számként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat egy [Object](../../system/object/) objektumként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat egy [Object](../../system/object/) objektumként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Beolvassa az aktuális elemet és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI megegyezik-e az aktuális eleméval, majd beolvassa az aktuális elemet és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Beolvassa a kizárólag szöveget tartalmazó elemet. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mivel ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott karakterlánccal, mielőtt beolvasná a kizárólag szöveget tartalmazó elemet. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mivel ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal, mielőtt beolvasná a kizárólag szöveget tartalmazó elemet. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mivel ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy záró címke, és a olvasót a következő csomópontra mozgatja. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Ha egy származtatott osztályban felülírják, akkor az összes tartalmat, beleértve a jelölőnyelvet, karakterláncként olvassa be. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Ha egy származtatott osztályban felülírják, akkor a csomópont és összes gyermekeleme által képviselt tartalmat, beleértve a jelölőnyelvet, beolvassa. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ellenőrzi, hogy a jelenlegi csomópont egy elem, és a olvasót a következő csomópontra mozgatja. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy adott [XmlReader::get_Name](../xmlreader/get_name/) értékkel rendelkező elem, és a olvasót a következő csomópontra mozgatja. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy adott [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékekkel rendelkező elem, és a olvasót a következő csomópontra mozgatja. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Beolvassa egy elem vagy szövegcsoport tartalmát karakterláncként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Visszaad egy új [XmlReader](../xmlreader/) példányt, amelyet a jelenlegi csomópont és minden leszármazott beolvasására lehet használni. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Előreviszi a [XmlReader](../xmlreader/)-t a megadott minősített névvel rendelkező következő leszármazott elemre. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Előreviszi a [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-vel rendelkező következő leszármazott elemre. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Olvasás addig, amíg a megadott minősített névvel rendelkező elem meg nem található. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Olvasás addig, amíg a megadott helyi névvel és névtér URI-vel rendelkező elem meg nem található. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Előreviszi a [XmlReader](../xmlreader/)-t a megadott minősített névvel rendelkező következő testvér elemre. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Előreviszi a [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-vel rendelkező következő testvér elemre. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Olvas nagy mennyiségű szöveget, amely XML-dokumentumba van beágyazva. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámot a megadott értékkel. |
| void [ResolveEntity](./resolveentity/)() override | Feloldja az entitás-referenciát **EntityReference** csomópontokhoz. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Skip](./skip/)() override | Átugorja a jelenlegi csomópont gyermekelemeit. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyéni objektumok karakterláncba konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Létrehozza a [XmlNodeReader](./) osztály egy példányát a megadott [XmlNode](../xmlnode/) használatával. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | A megosztott mutató aliasa erre az osztályra mutató példányhoz. |

## Megjegyzések

Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad allokálni. Soha ne hozzon létre példányokat ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert az objektum argumentumként való átadásához a függvényeknek. 

## Lásd még

* Osztály [XmlReader](../xmlreader/)
* Osztály [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Névterület [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)