---
title: XmlNodeReader
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een lezer voor die snelle, niet-gecachede, alleen-voorwaartse toegang tot XML-gegevens in een XmlNode biedt.
type: docs
weight: 365
url: /nl/system.xml/xmlnodereader/
---
## XmlNodeReader klasse


Stelt een lezer voor die snelle, niet-gecachede, alleen-voorwaartse toegang tot XML-gegevens in een [XmlNode](../xmlnode/) biedt.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Wijzigt de [XmlNodeReader::get_ReadState](./get_readstate/) naar [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met opgegeven URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met behulp van de opgegeven URI en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met behulp van de opgegeven URI, instellingen en contextinformatie voor parseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven stream met standaardinstellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven stream en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven stream, basis-URI en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven stream, instellingen en contextinformatie voor parseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met behulp van de opgegeven tekstlezer. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met behulp van de opgegeven tekstlezer en instellingen. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven tekstlezer, instellingen en basis-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven tekstlezer, instellingen en contextinformatie voor parseren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Maakt een nieuwe [XmlReader](../xmlreader/) instantie met de opgegeven XML-lezer en instellingen. |
| void [Dispose](../xmlreader/dispose/)() override | Vrijgeeft alle resources die door de huidige instantie van de [XmlReader](../xmlreader/) klasse worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Geeft het aantal attributen van het huidige knooppunt terug. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Geeft de basis-URI van het huidige knooppunt terug. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Geeft een waarde terug die aangeeft of de [XmlNodeReader](./) de methoden voor binaire inhoudslezen implementeert. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Geeft een waarde terug die aangeeft of de [XmlReader](../xmlreader/) de [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-methode implementeert. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Geeft een waarde terug die aangeeft of deze lezer entiteiten kan parseren en oplossen. |
| **int32_t** [get_Depth](./get_depth/)() override | Geeft de diepte van het huidige knooppunt in het XML-document terug. |
| **bool** [get_EOF](./get_eof/)() override | Geeft een waarde terug die aangeeft of de lezer zich aan het einde van de stream bevindt. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Geeft een waarde terug die aangeeft of het huidige knooppunt attributen heeft. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Geeft een waarde terug die aangeeft of het huidige knooppunt een [XmlNodeReader::get_Value](./get_value/)-waarde kan hebben. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Geeft een waarde terug die aangeeft of het huidige knooppunt een attribuut is dat is gegenereerd uit de standaardwaarde gedefinieerd in de documenttype-definitie (DTD) of het schema. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Geeft een waarde terug die aangeeft of het huidige knooppunt een leeg element is (bijvoorbeeld **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Geeft de lokale naam van het huidige knooppunt terug. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Geeft de gekwalificeerde naam van het huidige knooppunt terug. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Geeft de namespace-URI (zoals gedefinieerd in de W3C Namespace-specificatie) van het knooppunt waarop de lezer is gepositioneerd terug. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Geeft de [XmlNameTable](../xmlnametable/) die bij deze implementatie hoort terug. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Geeft het type van het huidige knooppunt terug. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Geeft het namespace-voorvoegsel dat bij het huidige knooppunt hoort terug. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Wanneer in een afgeleide klasse overschreven, krijgt het het aanhalingsteken-karakter dat wordt gebruikt om de waarde van een attribuutknooppunt te omsluiten. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Geeft de status van de lezer terug. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Geeft de schema-informatie terug die aan het huidige knooppunt is toegewezen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Geeft het [XmlReaderSettings](../xmlreadersettings/)-object terug dat wordt gebruikt om deze [XmlReader](../xmlreader/)-instantie te maken. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Geeft de tekstwaarde van het huidige knooppunt terug. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Geeft het type voor het huidige knooppunt terug. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Geeft de huidige **xml:lang**-scope terug. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Geeft de huidige **xml:space**-scope terug. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Geeft de waarde van het attribuut met de opgegeven naam terug. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Geeft de waarde van het attribuut met de opgegeven lokale naam en namespace-URI terug. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Geeft de waarde van het attribuut met de opgegeven index terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Wanneer in een afgeleide klasse overschreven, haalt het de waarde van het attribuut met de opgegeven index op. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Wanneer in een afgeleide klasse overschreven, haalt het de waarde van het attribuut met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/)-waarde op. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Wanneer in een afgeleide klasse overschreven, haalt het de waarde van het attribuut met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden op. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschreven door targetType vertegenwoordigt. Analoge van C# 'is'-operator. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Geeft een waarde terug die aangeeft of het string-argument een geldige XML-naam is. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Geeft een waarde terug die aangeeft of het string-argument een geldig XML-naam-token is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of een lege-element-tag is. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of een lege-element-tag is en of de [XmlReader::get_Name](../xmlreader/get_name/)-waarde van het gevonden element overeenkomt met het opgegeven argument. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Roept [XmlReader::MoveToContent](../xmlreader/movetocontent/) aan en test of het huidige inhoudsknooppunt een start-tag of een lege-element-tag is en of de [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden van het gevonden element overeenkomen met de opgegeven tekenreeksen. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Lost een namespace-voorvoegsel op in de scope van het huidige element. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Verplaatst zich naar het attribuut met de opgegeven naam. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Verplaatst zich naar het attribuut met de opgegeven lokale naam en namespace-URI. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Verplaatst zich naar het attribuut met de opgegeven index. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Controleert of het huidige knooppunt een inhouds-knooppunt is (tekst die geen witruimte is, **CDATA**, **Element**, **EndElement**, **EntityReference**, of **EndEntity**). Als het knooppunt geen inhouds-knooppunt is, slaat de lezer vooruit naar het volgende inhouds-knooppunt of het einde van het bestand. Het slaat knooppunten van de volgende typen over: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, of **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Verplaatst zich naar het element dat het huidige attribuutknooppunt bevat. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Verplaatst zich naar het eerste attribuut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Verplaatst zich naar het volgende attribuut. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| **bool** [Read](./read/)() override | Leest het volgende knooppunt uit de stream. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parset de attribuutwaarde in een of meer **[Text](../../system.text/)**, **EntityReference**, of **EndEntity**-knooppunten. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de inhoud als een object van het opgegeven type. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de Base64-gedecodeerde binaire bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Leest de tekstinhoud op de huidige positie als een [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Leest de tekstinhoud op de huidige positie als een [DateTime](../../system/datetime/)-object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Leest de tekstinhoud op de huidige positie als een [DateTimeOffset](../../system/datetimeoffset/)-object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Leest de tekstinhoud op de huidige positie als een [Decimal](../../system/decimal/)-object. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Leest de tekstinhoud op de huidige positie als een double-precisie zwevend-komma getal. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Leest de tekstinhoud op de huidige positie als een single-precisie zwevend-komma getal. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Leest de tekstinhoud op de huidige positie als een 32-bit ondertekend geheel getal. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Leest de tekstinhoud op de huidige positie als een 64-bit ondertekend geheel getal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Leest de tekstinhoud op de huidige positie als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Leest de tekstinhoud op de huidige positie als een [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Leest de elementinhoud als het aangevraagde type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens de elementinhoud als het aangevraagde type. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de Base64-inhoud. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Leest het element en decodeert de BinHex-inhoud. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Leest het huidige element en retourneert de inhoud als een [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Leest het huidige element en retourneert de inhoud als een [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Leest het huidige element en retourneert de inhoud als een [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Leest het huidige element en retourneert de inhoud als een dubbelprecisie floating-point-getal. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een dubbelprecisie floating-point-getal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Leest het huidige element en retourneert de inhoud als een enkele-precisie floating-point-getal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een enkele-precisie floating-point-getal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Leest het huidige element en retourneert de inhoud als een 32-bit ondertekend geheel getal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een 32-bit ondertekend geheel getal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Leest het huidige element en retourneert de inhoud als een 64-bit ondertekend geheel getal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een 64-bit ondertekend geheel getal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Leest het huidige element en retourneert de inhoud als een [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Leest het huidige element en retourneert de inhoud als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de opgegeven lokale naam en namespace-URI overeenkomen met die van het huidige element, en leest vervolgens het huidige element en retourneert de inhoud als een [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Leest een alleen-tekstelement. Het wordt echter aangeraden om de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat die een rechtlijnigere manier biedt om deze bewerking af te handelen. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Controleert of de [XmlReader::get_Name](../xmlreader/get_name/)-waarde van het gevonden element overeenkomt met de opgegeven tekenreeks voordat een alleen-tekstelement wordt gelezen. Het wordt echter aangeraden om de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat die een rechtlijnigere manier biedt om deze bewerking af te handelen. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Controleert of de [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden van het gevonden element overeenkomen met de opgegeven tekenreeksen voordat een alleen-tekstelement wordt gelezen. Het wordt echter aangeraden om de [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/)-methode te gebruiken, omdat die een rechtlijnigere manier biedt om deze bewerking af te handelen. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Controleert of het huidige content-node een eind-tag is en beweegt de lezer naar het volgende node. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Wanneer dit in een afgeleide klasse wordt overschreven, leest het alle inhoud, inclusief markup, als een string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Wanneer dit in een afgeleide klasse wordt overschreven, leest het de inhoud, inclusief markup, die dit node en al zijn kinderen vertegenwoordigt. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Controleert of het huidige node een element is en beweegt de lezer naar het volgende node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Controleert of het huidige content-node een element is met de opgegeven [XmlReader::get_Name](../xmlreader/get_name/)-waarde en beweegt de lezer naar het volgende node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Controleert of het huidige content-node een element is met de opgegeven [XmlReader::get_LocalName](../xmlreader/get_localname/)- en [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-waarden en beweegt de lezer naar het volgende node. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Leest de inhoud van een element- of tekstnode als een string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Retourneert een nieuwe [XmlReader](../xmlreader/)-instantie die kan worden gebruikt om het huidige node en al zijn afstammelingen te lezen. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende afstammende element met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende afstammende element met de opgegeven lokale naam en namespace-URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Leest tot een element met de opgegeven gekwalificeerde naam wordt gevonden. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Leest tot een element met de opgegeven lokale naam en namespace-URI wordt gevonden. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende broertjelement met de opgegeven gekwalificeerde naam. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Beweegt de [XmlReader](../xmlreader/) naar het volgende broertjelement met de opgegeven lokale naam en namespace-URI. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Leest grote tekststromen die in een XML-document zijn ingebed. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [ResolveEntity](./resolveentity/)() override | Lost de entiteitsreferentie op voor **EntityReference**-nodes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Skip](./skip/)() override | Slaat de kinderen van het huidige node over. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C#-methode [Object.ToString()](../../system/object/tostring/). Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C#-construct `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C#-`lock()`-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Creëert een instantie van de [XmlNodeReader](./)-klasse met de opgegeven [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijwaart alle interne datastructuren. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een gedeelde pointer naar een instantie van deze klasse. |
## Remarks

Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit instanties van dit type op de stack of met operator new, want dat leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om hem als argument aan functies door te geven. 

## See Also

* Klasse [XmlReader](../xmlreader/)
* Klasse [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namespace [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)