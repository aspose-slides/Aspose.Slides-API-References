---
title: XmlValidatingReader
second_title: Aspose.Slides for C++ API referencia
description: Olyan olvasót képvisel, amely biztosítja a dokumentumtípus-definíció (DTD), az XML-Data Reduced (XDR) séma és az XML Schema definíciós nyelv (XSD) validálását.
type: docs
weight: 547
url: /hu/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader osztály

Egy olvasót reprezentál, amely dokumentumtípus-definíciót (DTD), XML-Data Reduced (XDR) sémát és XML [Schema](../../system.xml.schema/) definíciós nyelvet (XSD) validál.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [Close](./close/)() override | A [XmlReader::get_ReadState](../xmlreader/get_readstate/)-t Closed állapotra változtatja. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI-val. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott URI, beállítások és a feldolgozáshoz szükséges kontextusinformációk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam használatával, alapértelmezett beállításokkal. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, alap URI és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott adatfolyam, beállítások és a feldolgozáshoz szükséges kontextusinformációk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó és beállítások használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és alap URI használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott szövegolvasó, beállítások és a feldolgozáshoz szükséges kontextusinformációk használatával. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Létrehoz egy új [XmlReader](../xmlreader/) példányt a megadott XML olvasó és beállítások használatával. |
| void [Dispose](../xmlreader/dispose/)() override | Felszabadítja az aktuális [XmlReader](../xmlreader/) osztálypéldány által használt összes erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékkel sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékkel sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Visszaadja az aktuális csomópont attribútumainak számát. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Visszaadja az aktuális csomópont alap URI-ját. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Visszaad egy értéket, amely jelzi, hogy a [XmlValidatingReader](./) implementálja-e a bináris tartalom olvasási metódusokat. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Visszaad egy értéket, amely jelzi, hogy a [XmlReader](../xmlreader/) implementálja-e a [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) metódust. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Visszaad egy értéket, amely jelzi, hogy ez az olvasó képes-e entitásokat feldolgozni és feloldani. |
| **int32_t** [get_Depth](./get_depth/)() override | Visszaadja az aktuális csomópont mélységét az XML dokumentumban. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Visszaadja a dokumentum kódolás attribútumát. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Visszaad egy értéket, amely meghatározza, hogyan kezeli az olvasó az entitásokat. |
| **bool** [get_EOF](./get_eof/)() override | Visszaad egy értéket, amely jelzi, hogy az olvasó a stream végén áll-e. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont rendelkezik-e attribútumokkal. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont lehet-e [XmlValidatingReader::get_Value](./get_value/) más, mint [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont egy attribútum-e, amely a dokumentumtípus-definíció (DTD) vagy séma alapértelmezett értékéből lett generálva. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Visszaad egy értéket, amely jelzi, hogy az aktuális csomópont egy üres elem-e (például **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Visszaadja az aktuális sor számát. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Visszaadja az aktuális sor pozícióját. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Visszaadja az aktuális csomópont helyi nevét. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Visszaadja az aktuális csomópont minősített nevét. |
| **bool** [get_Namespaces](./get_namespaces/)() | Visszaad egy értéket, amely jelzi, hogy legyen-e névtér támogatás. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Visszaadja a névtér Uniform Resource Identifier (URI) értékét (ahogy a World Wide [Web](../../system.web/) Consortium (W3C) Namespace specifikációban definiálták) annak a csomópontnak, amelyen az olvasó pozícionálva van. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Visszaadja a [XmlNameTable](../xmlnametable/)-t, amely ehhez a megvalósításhoz tartozik. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Visszaadja az aktuális csomópont típusát. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Visszaadja az aktuális csomóponthoz tartozó névtér előtagot. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Visszaadja az idézőjel karaktert, amelyet attribútumcsomópont értékének körülvételére használnak. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Visszaadja a [XmlReader](../xmlreader/)-t, amelyet ennek a [XmlValidatingReader](./)-nek a létrehozásához használnak. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Visszaadja az olvasó állapotát. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Visszaadja a sémainformációt, amelyet az aktuális csomóponthoz a séma validálás eredményeként rendelték. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Visszaad egy XmlSchemaCollection-t, amelyet validáláshoz használnak. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Visszaad egy séma típus objektumot. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Visszaadja a [XmlReaderSettings](../xmlreadersettings/) objektumot, amelyet ennek a [XmlReader](../xmlreader/) példánynak a létrehozásához használtak. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Visszaad egy értéket, amely jelzi a végrehajtandó validálás típusát. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Visszaadja az aktuális csomópont szöveges értékét. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Visszaadja az aktuális csomópont típusát. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Visszaadja az aktuális **xml:lang** környezetet. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Visszaadja az aktuális **xml:space** környezetet. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Visszaadja a megadott nevű attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Visszaadja a megadott helyi névvel és névtér Uniform Resource Identifier (URI)-val rendelkező attribútum értékét. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Visszaadja a megadott indexű attribútum értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Visszaad egy értéket, amely jelzi, hogy az osztály képes-e sorinformációt visszaadni. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Ha egy származtatott osztályban felül van definiálva, lekéri a megadott indexű attribútum értékét. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, lekéri a megadott [XmlReader::get_Name](../xmlreader/get_name/) értékű attribútum értékét. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Ha egy származtatott osztályban felül van definiálva, lekéri a megadott [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékű attribútum értékét. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely jelzi, hogy a karakterlánc argumentum érvényes XML név-e. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Visszaad egy értéket, amely jelzi, hogy a karakterlánc argumentum érvényes XML név token-e vagy sem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t és teszteli, hogy az aktuális tartalomcsomópont kezdő címke vagy üres elem címke-e. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t és teszteli, hogy az aktuális tartalomcsomópont kezdő címke vagy üres elem címke-e, és hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott argumentummal. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Meghívja a [XmlReader::MoveToContent](../xmlreader/movetocontent/)-t és teszteli, hogy az aktuális tartalomcsomópont kezdő címke vagy üres elem címke-e, és hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Felold egy névtér előtagot az aktuális elem hatókörében. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Áthelyez a megadott nevű attribútumra. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Áthelyez a megadott helyi névvel és névtér Uniform Resource Identifier (URI)-val rendelkező attribútumra. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Áthelyez a megadott indexű attribútumra. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Ellenőrzi, hogy az aktuális csomópont tartalom (nem whitespace szöveg, **CDATA**, **Element**, **EndElement**, **EntityReference**, vagy **EndEntity**) csomópont-e. Ha a csomópont nem tartalom, az olvasó a következő tartalomcsomópontra vagy a fájl végére ugrik. A következő típusú csomópontokat hagyja át: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, vagy **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Áthelyez arra az elemre, amely a jelenlegi attribútumcsomópontot tartalmazza. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Áthelyez az első attribútumra. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Áthelyez a következő attribútumra. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolatkészítését. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolatkészítését. |
| **bool** [Read](./read/)() override | Beolvassa a következő csomópontot a stream-ből. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Az attribútum értékét egy vagy több **[Text](../../system.text/)**, **EntityReference**, vagy **EndEntity** csomóppá dolgozza fel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | A tartalmat a megadott típusú objektumként olvassa. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat és visszaadja a Base64-dekódolt bináris bájtokat. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa a tartalmat és visszaadja a BinHex-dekódolt bináris bájtokat. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [Boolean](../../system/boolean/)-ként. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [DateTimeOffset](../../system/datetimeoffset/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [Decimal](../../system/decimal/) objektumként. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Beolvassa a szövegtartalmat az aktuális pozícióban dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Beolvassa a szövegtartalmat az aktuális pozícióban egyszeres pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Beolvassa a szövegtartalmat az aktuális pozícióban 32 bites előjeles egészként. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Beolvassa a szövegtartalmat az aktuális pozícióban 64 bites előjeles egészként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [Object](../../system/object/)-ként. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Beolvassa a szövegtartalmat az aktuális pozícióban [String](../../system/string/) objektumként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Beolvassa az elem tartalmát a kért típus szerint. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az elem tartalmát a kért típus szerint. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet, és dekódolja a Base64 tartalmat. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Beolvassa az elemet, és dekódolja a BinHex tartalmat. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat [Boolean](../../system/boolean/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat [DateTime](../../system/datetime/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat [Decimal](../../system/decimal/) objektumként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat dupla pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat egyszeres pontosságú lebegőpontos számként. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat egyszeres pontosságú lebegőpontos számként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat 32 bites előjeles egészként. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat 32 bites előjeles egészként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat 64 bites előjeles egészként. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat 64 bites előjeles egészként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat [Object](../../system/object/)-ként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat [Object](../../system/object/)-ként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Beolvassa az aktuális elemet, és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat [String](../../system/string/) objektumként. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Beolvassa a csak szöveget tartalmazó elemet. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_Name](../xmlreader/get_name/) értéke megegyezik-e a megadott karakterlánccal, mielőtt csak szöveget tartalmazó elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a megtalált elem [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal, mielőtt csak szöveget tartalmazó elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metódust használni helyette, mert ez egyszerűbb módot biztosít a művelet kezelésére. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy záró címke, és a olvasót a következő csomópontra lépteti. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Ha felülírják egy leszármazott osztályban, beolvassa az összes tartalmat, beleértve a jelölőket, karakterláncként. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Ha felülírják egy leszármazott osztályban, beolvassa a tartalmat, beleértve a jelölőket, amely ezt a csomópontot és annak összes gyermekét ábrázolja. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ellenőrzi, hogy a jelenlegi csomópont egy elem, és a olvasót a következő csomópontra lépteti. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy olyan elem, amelynek a [XmlReader::get_Name](../xmlreader/get_name/) értéke adott, és a olvasót a következő csomópontra lépteti. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ellenőrzi, hogy a jelenlegi tartalomcsomópont egy olyan elem, amelynek a [XmlReader::get_LocalName](../xmlreader/get_localname/) és [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) értékei adottak, és a olvasót a következő csomópontra lépteti. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Beolvassa egy elem vagy szövegcsoport tartalmát karakterláncként. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Visszaad egy új [XmlReader](../xmlreader/) példányt, amelyet a jelenlegi csomópont és annak összes leszármazottja olvasására lehet használni. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott minősített névvel rendelkező következő leszármazott elemre lépteti. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-val rendelkező következő leszármazott elemre lépteti. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Olvas, amíg a megadott minősített névvel rendelkező elem meg nem jelenik. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Olvas, amíg a megadott helyi névvel és névtér URI-val rendelkező elem meg nem jelenik. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott minősített névvel rendelkező következő testvér elemre lépteti. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | A [XmlReader](../xmlreader/)-t a megadott helyi névvel és névtér URI-val rendelkező következő testvér elemre lépteti. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Visszaadja a futásidejű típust a megadott XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) típusa számára. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Nagy mennyiségű szöveget olvas be, amely XML-dokumentumba be van ágyazva. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot hasonlít össze nullptr-re hivatkozással. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [ResolveEntity](./resolveentity/)() override | Feloldja az entitásreferenciát a **EntityReference** csomópontokhoz. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Beállít egy értéket, amely meghatározza, hogyan kezeli az olvasó az entitásokat. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Beállít egy értéket, amely jelzi, hogy szükséges-e a névtér támogatás. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Beállít egy értéket, amely jelzi a végrehajtandó validáció típusát. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Beállítja a [XmlResolver](../xmlresolver/)-t, amelyet a külső dokumentumtípus-definíció (DTD) és sémahely hivatkozások feloldásához használnak. A [XmlResolver](../xmlresolver/) szintén az XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) sémákban található import vagy include elemek kezelésére szolgál. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n. sablonargumentumot gyenge mutatóként (nem megosztott) állítja be. Lehetővé teszi a mutatók átkapcsolását a gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti, és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [Skip](../xmlreader/skip/)() | Kihagyja a jelenlegi csomópont gyermekeit. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódusának analógja. Lehetővé teszi egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítást feloldásra. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Eseménykezelőt ad hozzá a dokumentumtípus-definíció (DTD), XML-Data Reduced (XDR) séma, valamint XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) séma validálási hibáiról szóló információk fogadásához. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Eseménykezelőt távolít el a dokumentumtípus-definíció (DTD), XML-Data Reduced (XDR) séma, valamint XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) séma validálási hibáiról szóló információk fogadásához. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Inicializál egy új [XmlValidatingReader](./) osztálypéldányt, amely ellenőrzi a megadott [XmlReader](../xmlreader/) által visszaadott tartalmat. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializál egy új [XmlValidatingReader](./) osztálypéldányt a megadott értékekkel. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializál egy új [XmlValidatingReader](./) osztálypéldányt a megadott értékekkel. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Alias egy megosztott mutatóhoz, amely ennek az osztálynak egy példányára mutat. |
## Megjegyzések

Elavult
:   Ez az osztály elavult. Ajánlott a [XmlReaderSettings](../xmlreadersettings/) osztályt és a [XmlReader::Create](../xmlreader/create/) metódust használni egy validáló XML olvasó létrehozásához.
Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányokat ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert, hogy argumentumként átadja a függvényeknek.

## Lásd még

* Osztály [XmlReader](../xmlreader/)
* Osztály [IXmlLineInfo](../ixmllineinfo/)
* Osztály [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Névtér [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)