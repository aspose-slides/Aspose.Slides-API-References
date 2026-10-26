---
title: XmlValidatingReader
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een lezer die documenttype-definitie (DTD), XML-Data Reduced (XDR)-schema en XML Schema definitietaal (XSD) validatie biedt.
type: docs
weight: 547
url: /nl/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader klasse


Stelt een lezer voor die documenttype-definitie (DTD), XML-Data Reduced (XDR) schema en XML [Schema](../../system.xml.schema/) definitietaal (XSD) validatie biedt.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Wijzigt de [XmlReader::get_ReadState](../xmlreader/get_readstate/) naar Gesloten. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met opgegeven URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven URI en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven URI, instellingen en contextinformatie voor het analyseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met de opgegeven stroom en standaardinstellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met de opgegeven stroom en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met de opgegeven stroom, basis-URI en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met de opgegeven stroom, instellingen en contextinformatie voor het analyseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven tekstreder. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven tekstreder en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven tekstreder, instellingen en basis-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven tekstreder, instellingen en contextinformatie voor het analyseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Maakt een nieuw [XmlReader](../xmlreader/)-exemplaar met behulp van de opgegeven XML-lezer en instellingen. |
| void [Dispose](../xmlreader/dispose/)() override | Geeft alle resources vrij die door de huidige instantie van de [XmlReader](../xmlreader/)-klasse worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Retourneert het aantal attributen op het huidige knooppunt. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Retourneert de basis-URI van het huidige knooppunt. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Retourneert een waarde die aangeeft of de [XmlValidatingReader](./) de binaire-inhoud-leescodes implementeert. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Retourneert een waarde die aangeeft of de [XmlReader](../xmlreader/) de [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-methode implementeert. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Retourneert een waarde die aangeeft of deze lezer entiteiten kan analyseren en oplossen. |
| **int32_t** [get_Depth](./get_depth/)() override | Retourneert de diepte van het huidige knooppunt in het XML-document. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Retourneert het coderingsattribuut voor het document. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Retourneert een waarde die aangeeft hoe de lezer omgaat met entiteiten. |
| **bool** [get_EOF](./get_eof/)() override | Retourneert een waarde die aangeeft of de lezer zich aan het einde van de stroom bevindt. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Retourneert een waarde die aangeeft of het huidige knooppunt attributen heeft. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een [XmlValidatingReader::get_Value](./get_value/) kan hebben anders dan [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een attribuut is dat gegenereerd is vanuit de standaardwaarde gedefinieerd in de documenttype-definitie (DTD) of het schema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een leeg element is (bijvoorbeeld **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Retourneert het huidige regelnummer. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Retourneert de huidige regelpositie. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retourneert de lokale naam van het huidige knooppunt. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourneert de gekwalificeerde naam van het huidige knooppunt. |
| **bool** [get_Namespaces](./get_namespaces/)() | Retourneert een waarde die aangeeft of namespace-ondersteuning moet worden uitgevoerd. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Retourneert de Uniform Resource Identifier (URI) van de namespace (zoals gedefinieerd in de World Wide [Web](../../system.web/) Consortium (W3C) Namespace-specificatie) van het knooppunt waarop de lezer zich bevindt. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Retourneert de [XmlNameTable](../xmlnametable/) die aan deze implementatie is gekoppeld. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retourneert het type van het huidige knooppunt. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Retourneert het namespace-voorvoegsel dat aan het huidige knooppunt is gekoppeld. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Retourneert het aanhalingsteken dat gebruikt wordt om de waarde van een attribuutknooppunt te omgeven. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Retourneert de [XmlReader](../xmlreader/) die gebruikt wordt om deze [XmlValidatingReader](./) te construeren. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Retourneert de status van de lezer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Retourneert de schemainformatie die aan het huidige knooppunt is toegewezen als gevolg van schema-validatie. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Retourneert een XmlSchemaCollection die gebruikt kan worden voor validatie. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Retourneert een schema-type-object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Retourneert het [XmlReaderSettings](../xmlreadersettings/)-object dat gebruikt wordt om deze [XmlReader](../xmlreader/)-instantie te maken. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Retourneert een waarde die het type validatie aangeeft dat uitgevoerd moet worden. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Retourneert de tekstwaarde van het huidige knooppunt. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Retourneert het type voor het huidige knooppunt. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retourneert de huidige **xml:lang**-scope. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retourneert de huidige **xml:space**-scope. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Retourneert de waarde van het attribuut met de opgegeven naam. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace-Uniform Resource Identifier (URI). |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Retourneert de waarde van het attribuut met de opgegeven index. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Retourneert een waarde die aangeeft of de klasse lijn-informatie kan retourneren. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Wanneer deze in een afgeleide klasse wordt overschreven, haalt de waarde op van het attribuut met de opgegeven index. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Wanneer deze in een afgeleide klasse wordt overschreven, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/)-waarde. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Wanneer deze in een afgeleide klasse wordt overschreven, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Retourneert een waarde die aangeeft of het tekenreeks-argument een geldige XML-naam is. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Retourneert een waarde die aangeeft of het tekenreeks-argument een geldig XML-naam-token is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is en of de [XmlReader::get_Name](../xmlreader/get_name/)-waarde van het gevonden element overeenkomt met het gegeven argument. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is en of de [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden van het gevonden element overeenkomen met de gegeven strings. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Lost een namespace-voorvoegsel op in de scope van het huidige element. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt het klonen van aangepaste types mogelijk. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Verplaatst naar het attribuut met de opgegeven naam. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Verplaatst naar het attribuut met de opgegeven lokale naam en namespace-Uniform Resource Identifier (URI). |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Verplaatst naar het attribuut met de opgegeven index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Controleert of het huidige knooppunt een inhouds-knooppunt is (tekst die geen witruimte is, **CDATA**, **Element**, **EndElement**, **EntityReference**, of **EndEntity**). Als het knooppunt geen inhouds-knooppunt is, slaat de lezer vooruit naar het volgende inhouds-knooppunt of het einde van het bestand. Het slaat knooppunten van de volgende typen over: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, of **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Verplaatst naar het element dat het huidige attribuutknooppunt bevat. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Verplaatst naar het eerste attribuut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Verplaatst naar het volgende attribuut. |
|  [Object](../../system/object/object/)() | Maakt object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| **bool** [Read](./read/)() override | Leest het volgende knooppunt van de stroom. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parseert de attribuutwaarde naar één of meer **[Text](../../system.text/)**, **EntityReference**, of **EndEntity**-knooppunten. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de inhoud als een object van het gespecificeerde type. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de Base64-gedecodeerde binaire bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Leest de tekstinhoud op de huidige positie als een [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Leest de tekstinhoud op de huidige positie als een [DateTime](../../system/datetime/) object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Leest de tekstinhoud op de huidige positie als een [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Leest de tekstinhoud op de huidige positie als een [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Leest de tekstinhoud op de huidige positie als een double-precision floating-point getal. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Leest de tekstinhoud op de huidige positie als een single-precision floating point getal. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Leest de tekstinhoud op de huidige positie als een 32-bit signed integer. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Leest de tekstinhoud op de huidige positie als een 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Leest de tekstinhoud op de huidige positie als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Leest de tekstinhoud op de huidige positie als een [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de elementinhoud als het gevraagde type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens de elementinhoud als het gevraagde type. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de Base64-inhoud. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de BinHex-inhoud. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Leest het huidige element en geeft de inhoud terug als een [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Leest het huidige element en geeft de inhoud terug als een [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Leest het huidige element en geeft de inhoud terug als een [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Leest het huidige element en geeft de inhoud terug als een double-precision floating-point getal. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een double-precision floating-point getal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Leest het huidige element en geeft de inhoud terug als een single-precision floating-point getal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een single-precision floating-point getal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Leest het huidige element en geeft de inhoud terug als een 32-bit signed integer. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een 32-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Leest het huidige element en geeft de inhoud terug als een 64-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Leest het huidige element en geeft de inhoud terug als een [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Leest het huidige element en geeft de inhoud terug als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en geeft de inhoud terug als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Leest een alleen-tekst-element. Het wordt echter aanbevolen om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking uit te voeren. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Controleert of de [XmlReader::get_Name](../xmlreader/get_name/)-waarde van het gevonden element overeenkomt met de opgegeven tekenreeks vóór het lezen van een alleen-tekst-element. Het wordt echter aanbevolen om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking uit te voeren. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de [XmlReader::get_LocalName](../xmlreader/get_localname/) en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden van het gevonden element overeenkomen met de opgegeven tekenreeksen vóór het lezen van een alleen-tekst-element. Het wordt echter aanbevolen om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking uit te voeren. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Controleert of het huidige inhoudsknooppunt een eind-tag is en beweegt de lezer naar het volgende knooppunt. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Wanneer overschreven in een afgeleide klasse, leest alle inhoud, inclusief opmaak, als een tekenreeks. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Wanneer overschreven in een afgeleide klasse, leest de inhoud, inclusief opmaak, die dit knooppunt en al zijn kinderen vertegenwoordigt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Controleert of het huidige knooppunt een element is en beweegt de lezer naar het volgende knooppunt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Controleert of het huidige inhoudsknooppunt een element is met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/)-waarde en beweegt de lezer naar het volgende knooppunt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Controleert of het huidige inhoudsknooppunt een element is met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/) en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden en beweegt de lezer naar het volgende knooppunt. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Leest de inhoud van een element- of tekstknooppunt als een tekenreeks. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Retourneert een nieuwe [XmlReader](../xmlreader/)-instantie die kan worden gebruikt om het huidige knooppunt en al zijn afstammelingen te lezen. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende afstammende element met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende afstammende element met de opgegeven lokale naam en namespace-URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Leest tot een element met de opgegeven gekwalificeerde naam wordt gevonden. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Leest tot een element met de opgegeven lokale naam en namespace-URI wordt gevonden. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende broerelement met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende broerelement met de opgegeven lokale naam en namespace-URI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Retourneert het runt-ime type voor het opgegeven XML [Schema](../../system.xml.schema/) definitietaal (XSD) type. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Leest grote tekststromen die zijn ingebed in een XML-document. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [ResolveEntity](./resolveentity/)() override | Lost het entiteit-referentie voor **EntityReference** knooppunten. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Stelt een waarde in die aangeeft hoe de lezer entiteiten verwerkt. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Stelt een waarde in die aangeeft of namespaces worden ondersteund. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Stelt een waarde in die het type validatie aangeeft dat moet worden uitgevoerd. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Stelt de [XmlResolver](../xmlresolver/) in die wordt gebruikt voor het oplossen van externe documenttype-definitie (DTD) en schema-locatierreferenties. De [XmlResolver](../xmlresolver/) wordt ook gebruikt om eventuele import- of include-elementen te verwerken die in XML [Schema](../../system.xml.schema/) definitietaal (XSD) schema's worden gevonden. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-templaatargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Slaat de kinderen van het huidige knooppunt over. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt conversie van aangepaste objecten naar tekenreeks in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Voegt een gebeurtenis-handler toe voor het ontvangen van informatie over documenttype-definitie (DTD), XML-Data Reduced (XDR) schema, en XML [Schema](../../system.xml.schema/) definitietaal (XSD) schema-validatiefouten. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Verwijdert een gebeurtenis-handler voor het ontvangen van informatie over documenttype-definitie (DTD), XML-Data Reduced (XDR) schema, en XML [Schema](../../system.xml.schema/) definitietaal (XSD) schema-validatiefouten. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlValidatingReader](./)-klasse die de inhoud valideert die wordt geretourneerd door de opgegeven [XmlReader](../xmlreader/). |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlValidatingReader](./)-klasse met de opgegeven waarden. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlValidatingReader](./)-klasse met de opgegeven waarden. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor gedeelde pointer naar een instantie van deze klasse. |

## Opmerkingen

Verouderd
:   Deze klasse is verouderd. Het wordt aanbevolen om de [XmlReaderSettings](../xmlreadersettings/) klasse en de [XmlReader::Create](../xmlreader/create/) methode te gebruiken om een XML-lezer met validatie te maken.
Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit exemplaren van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. 

## Zie ook

* Klasse [XmlReader](../xmlreader/)
* Klasse [IXmlLineInfo](../ixmllineinfo/)
* Klasse [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)