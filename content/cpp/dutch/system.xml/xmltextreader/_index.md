---
title: XmlTextReader
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een lezer voor die snelle, niet-gebufferde, alleen-voorwaartse toegang tot XML-gegevens biedt.
type: docs
weight: 508
url: /nl/system.xml/xmltextreader/
---
## XmlTextReader klasse

Stelt een lezer voor die snelle, niet-gecachede, alleen-voorwaartse toegang tot XML-gegevens biedt.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Verandert de [XmlReader::get_ReadState](../xmlreader/get_readstate/) naar **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie met de opgegeven URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven URI en instellingen te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven URI, instellingen en contextinformatie voor het parseren te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie met de opgegeven stream en standaardinstellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie met de opgegeven stream en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie met de opgegeven stream, basis-URI en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie met de opgegeven stream, instellingen en contextinformatie voor het parseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven tekstlezer te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven tekstlezer en instellingen te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven tekstlezer, instellingen en basis-URI te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven tekstlezer, instellingen en contextinformatie voor het parseren te gebruiken. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Maakt een nieuwe [XmlReader](../xmlreader/)-instantie door de opgegeven XML-lezer en instellingen te gebruiken. |
| void [Dispose](../xmlreader/dispose/)() override | Geeft alle resources vrij die door de huidige instantie van de [XmlReader](../xmlreader/)-klasse worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige vergelijking van drijvende-kommagetallen waarbij twee NaN's als gelijk worden beschouwd, zelfs alhoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige vergelijking van drijvende-kommagetallen waarbij twee NaN's als gelijk worden beschouwd, zelfs alhoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Retourneert het aantal attributen op het huidige knooppunt. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Retourneert de basis-URI van het huidige knooppunt. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Retourneert een waarde die aangeeft of de [XmlTextReader](./) de binaire inhoudleesmethoden implementeert. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Retourneert een waarde die aangeeft of de [XmlTextReader](./) de [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-methode implementeert. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Retourneert een waarde die aangeeft of deze lezer entiteiten kan parseren en oplossen. |
| **int32_t** [get_Depth](./get_depth/)() override | Retourneert de diepte van het huidige knooppunt in het XML-document. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Retourneert de DtdProcessing-enumeratie. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Retourneert de codering van het document. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Retourneert een waarde die aangeeft hoe de lezer met entiteiten omgaat. |
| **bool** [get_EOF](./get_eof/)() override | Retourneert een waarde die aangeeft of de lezer zich aan het einde van de stream bevindt. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Retourneert een waarde die aangeeft of het huidige knooppunt attributen heeft. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een [XmlTextReader::get_Value](./get_value/) kan hebben die anders is dan [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een attribuut is dat is gegenereerd uit de standaardwaarde gedefinieerd in de DTD of het schema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Retourneert een waarde die aangeeft of het huidige knooppunt een leeg element is (bijvoorbeeld **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Retourneert het huidige regelnummer. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Retourneert de huidige regelpositie. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Retourneert de lokale naam van het huidige knooppunt. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourneert de gekwalificeerde naam van het huidige knooppunt. |
| **bool** [get_Namespaces](./get_namespaces/)() | Retourneert een waarde die aangeeft of namespace-ondersteuning moet worden toegepast. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Retourneert de namespace-URI (zoals gedefinieerd in de W3C Namespace-specificatie) van het knooppunt waarop de lezer is gepositioneerd. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Retourneert de [XmlNameTable](../xmlnametable/) die bij deze implementatie hoort. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Retourneert het type van het huidige knooppunt. |
| **bool** [get_Normalization](./get_normalization/)() | Retourneert een waarde die aangeeft of witruimte en attribuutwaarden moeten worden genormaliseerd. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Retourneert het namespace-prefix dat aan het huidige knooppunt is gekoppeld. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Retourneert een waarde die aangeeft of DTD-verwerking is toegestaan. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Retourneert het aanhalingsteken dat wordt gebruikt om de waarde van een attribuutknooppunt te omsluiten. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Retourneert de staat van de lezer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Retourneert de schemainformatie die aan het huidige knooppunt is toegewezen als gevolg van schema-validatie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Retourneert het [XmlReaderSettings](../xmlreadersettings/)-object dat wordt gebruikt om deze [XmlReader](../xmlreader/)-instantie te maken. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Retourneert de tekstwaarde van het huidige knooppunt. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Retourneert het type van het huidige knooppunt. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Retourneert een waarde die aangeeft hoe witruimte wordt behandeld. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Retourneert de huidige **xml:lang**-scope. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Retourneert de huidige **xml:space**-scope. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Retourneert de waarde van het attribuut met de opgegeven naam. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace-URI. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Retourneert de waarde van het attribuut met de opgegeven index. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt het hashen van aangepaste objecten in. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Retourneert een collectie die alle momenteel in scope zijnde namespaces bevat. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Retourneert de rest van de gebufferde XML. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Retourneert een waarde die aangeeft of de klasse regelinformatie kan teruggeven. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Wanneer overschreven in een afgeleide klasse, haalt de waarde van het attribuut op met de opgegeven index. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, haalt de waarde van het attribuut op met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/)-waarde. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Wanneer overschreven in een afgeleide klasse, haalt de waarde van het attribuut op met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is'-operator. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Retourneert een waarde die aangeeft of het tekenreeksargument een geldige XML-naam is. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Retourneert een waarde die aangeeft of het tekenreeksargument een geldig XML-naamtoken is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is en of de [XmlReader::get_Name](../xmlreader/get_name/)-waarde van het gevonden element overeenkomt met het opgegeven argument. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of lege-element-tag is en of de [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden van het gevonden element overeenkomen met de opgegeven strings. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling volgens de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Lost een namespace-prefix op in de scope van het huidige element. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste typen in. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Verplaatst naar het attribuut met de opgegeven naam. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Verplaatst naar het attribuut met de opgegeven lokale naam en namespace-URI. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Verplaatst naar het attribuut met de opgegeven index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Controleert of het huidige knooppunt een inhoudsknooppunt is (niet-witruimte-tekst, **CDATA**, **Element**, **EndElement**, **EntityReference**, of **EndEntity**). Als het knooppunt geen inhoudsknooppunt is, slaat de lezer vooruit naar het volgende inhoudsknooppunt of einde van bestand. Het slaat knooppunten van de volgende types over: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, of **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Verplaatst naar het element dat het huidige attribuutknooppunt bevat. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Verplaatst naar het eerste attribuut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Verplaatst naar het volgende attribuut. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| **bool** [Read](./read/)() override | Leest het volgende knooppunt uit de stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parseert de attribuutwaarde naar één of meer **[Text](../../system.text/)**, **EntityReference**, of **EndEntity**-knooppunten. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Decodeert Base64 en retourneert de gedecodeerde binaire bytes. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Decodeert **BinHex** en retourneert de gedecodeerde binaire bytes. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Leest de tekstinhoud van een element in een tekenbuffer. Deze methode is ontworpen om grote stromen van ingebedde tekst te lezen door deze opeenvolgend aan te roepen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de inhoud als een object van het opgegeven type. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de **Base64** gedecodeerde binaire bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de **BinHex** gedecodeerde binaire bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Leest de tekstinhoud op de huidige positie als een [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Leest de tekstinhoud op de huidige positie als een [DateTime](../../system/datetime/) object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Leest de tekstinhoud op de huidige positie als een [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Leest de tekstinhoud op de huidige positie als een [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Leest de tekstinhoud op de huidige positie als een double-precisie zwevend-kommagetal. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Leest de tekstinhoud op de huidige positie als een single-precisie zwevend-kommagetal. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Leest de tekstinhoud op de huidige positie als een 32-bits ondertekend geheel getal. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Leest de tekstinhoud op de huidige positie als een 64-bits ondertekend geheel getal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Leest de tekstinhoud op de huidige positie als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Leest de tekstinhoud op de huidige positie als een [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de elementinhoud als het gevraagde type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens de elementinhoud als het gevraagde type. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de Base64-inhoud. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de **BinHex**-inhoud. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Leest het huidige element en retourneert de inhoud als een [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Leest het huidige element en retourneert de inhoud als een [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Leest het huidige element en retourneert de inhoud als een [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Leest het huidige element en retourneert de inhoud als een double-precisie zwevend-kommagetal. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een double-precisie zwevend-kommagetal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Leest het huidige element en retourneert de inhoud als een single-precisie zwevend-kommagetal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een single-precisie zwevend-kommagetal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Leest het huidige element en retourneert de inhoud als een 32-bits ondertekend geheel getal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een 32-bits ondertekend geheel getal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Leest het huidige element en retourneert de inhoud als een 64-bits ondertekend geheel getal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een 64-bits ondertekend geheel getal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Leest het huidige element en retourneert de inhoud als een [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Leest het huidige element en retourneert de inhoud als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Leest een alleen-tekst element. Het wordt echter aangeraden om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking af te handelen. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Controleert dat de [XmlReader::get_Name](../xmlreader/get_name/) waarde van het gevonden element overeenkomt met de opgegeven string voordat een alleen-tekst element wordt gelezen. Het wordt echter aangeraden om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking af te handelen. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert dat de [XmlReader::get_LocalName](../xmlreader/get_localname/) en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) waarden van het gevonden element overeenkomen met de opgegeven strings voordat een alleen-tekst element wordt gelezen. Het wordt echter aangeraden om in plaats daarvan de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) methode te gebruiken, omdat deze een eenvoudigere manier biedt om deze bewerking af te handelen. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Controleert of de huidige inhoudsknoop een eindtag is en laat de lezer naar de volgende knoop gaan. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Wanneer overschreven in een afgeleide klasse, leest alle inhoud, inclusief markup, als een tekenreeks. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Wanneer overschreven in een afgeleide klasse, leest de inhoud, inclusief markup, die deze knoop en al zijn kinderen vertegenwoordigt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Controleert of de huidige knoop een element is en laat de lezer naar de volgende knoop gaan. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Controleert of de huidige inhoudsknoop een element is met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/) waarde en laat de lezer naar de volgende knoop gaan. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de huidige inhoudsknoop een element is met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/) en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) waarden en laat de lezer naar de volgende knoop gaan. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Leest de inhoud van een element of een tekstknoop als een tekenreeks. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Retourneert een nieuw [XmlReader](../xmlreader/) exemplaar dat kan worden gebruikt om de huidige knoop en al zijn afstammelingen te lezen. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Verplaatst de [XmlReader](../xmlreader/) naar het volgende afstammelingselement met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XmlReader](../xmlreader/) naar het volgende afstammelingselement met de opgegeven lokale naam en namespace-URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Leest tot een element met de opgegeven gekwalificeerde naam wordt gevonden. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Leest tot een element met de opgegeven lokale naam en namespace-URI wordt gevonden. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Verplaatst de [XmlReader](../xmlreader/) naar het volgende broerelement met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Verplaatst de [XmlReader](../xmlreader/) naar het volgende broerelement met de opgegeven lokale naam en namespace-URI. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Leest grote stromen van tekst die in een XML-document zijn ingebed. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt het waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [ResetState](./resetstate/)() | Reset de status van de lezer naar [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Lost de entiteitsreferentie op voor **EntityReference** knopen. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Stelt de DtdProcessing enumeratie in. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Stelt een waarde in die specificeert hoe de lezer met entiteiten omgaat. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Stelt een waarde in die aangeeft of namespace-ondersteuning moet worden toegepast. |
| void [set_Normalization](./set_normalization/)(**bool**) | Stelt een waarde in die aangeeft of witte ruimte en attribuutwaarden genormaliseerd moeten worden. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Stelt een waarde in die aangeeft of DTD-verwerking is toegestaan. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Stelt een waarde in die specificeert hoe witte ruimte wordt behandeld. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Stelt de [XmlResolver](../xmlresolver/) in die wordt gebruikt voor het oplossen van DTD-referenties. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Skip](./skip/)() override | Slaat de kinderen van de huidige knoop over. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het mogelijk om aangepaste objecten naar een tekenreeks te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendelen. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven stream. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven URL en stream. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven stream en [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven URL, stream en [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven URL en TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven TextReader en [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven URL, TextReader en [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven stream, XmlNodeType en [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met de opgegeven string, XmlNodeType en [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met het opgegeven bestand. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initialiseert een nieuw exemplaar van de [XmlTextReader](./) klasse met het opgegeven bestand en [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Bevrijdt alle interne datastructuren. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |
## Opmerkingen



Het wordt aanbevolen om in plaats daarvan de [XmlReader](../xmlreader/) klasse te gebruiken. 

Objecten van deze klasse mogen alleen worden toegewezen met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit instanties van dit type op de stack of met operator new, aangezien dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument. 

## Zie ook

* Klasse [XmlReader](../xmlreader/)
* Klasse [IXmlLineInfo](../ixmllineinfo/)
* Klasse [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)