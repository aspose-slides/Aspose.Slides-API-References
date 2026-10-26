---
title: XmlNodeReader
second_title: Aspose.Slides för C++ API-referens
description: Representerar en läsare som ger snabb, icke-cachad, endast framåtriktad åtkomst till XML-data i en XmlNode.
type: docs
weight: 365
url: /sv/system.xml/xmlnodereader/
---
## XmlNodeReader klass


Representerar en läsare som ger snabb, icke-cachad, endast framåtriktad åtkomst till XML-data i en [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Close](./close/)() override | Ändrar [XmlNodeReader::get_ReadState](./get_readstate/) till [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med angivet URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna URI:n och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna URI:n, inställningarna och kontextinformationen för tolkning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen och standardinställningar. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen, bas-URI och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen, inställningarna och kontextinformationen för tolkning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren, inställningarna och bas-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren, inställningarna och kontextinformationen för tolkning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna XML-läsaren och inställningarna. |
| void [Dispose](../xmlreader/dispose/)() override | Frigör alla resurser som används av den aktuella instansen av [XmlReader](../xmlreader/)-klassen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Returnerar antalet attribut på den aktuella noden. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Returnerar bas-URI för den aktuella noden. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returnerar ett värde som indikerar om [XmlNodeReader](./) implementerar metoderna för läsning av binärt innehåll. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Returnerar ett värde som indikerar om [XmlReader](../xmlreader/) implementerar [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-metoden. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Returnerar ett värde som indikerar om denna läsare kan tolka och lösa entiteter. |
| **int32_t** [get_Depth](./get_depth/)() override | Returnerar djupet för den aktuella noden i XML-dokumentet. |
| **bool** [get_EOF](./get_eof/)() override | Returnerar ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Returnerar ett värde som indikerar om den aktuella noden kan ha ett [XmlNodeReader::get_Value](./get_value/)-värde. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett attribut som genererades från standardvärdet definierat i dokumenttypdefinitionen (DTD) eller schemat. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett tomt element (till exempel **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på den aktuella noden. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymds-URI (enligt W3C:s namnrymdspecifikation) för den nod som läsaren är placerad på. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Returnerar [XmlNameTable](../xmlnametable/) som är associerad med denna implementation. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Returnerar typen för den aktuella noden. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet som är associerat med den aktuella noden. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | När den överskuggas i en avledd klass hämtas tecknet för citationstecken som används för att omge värdet på ett attributnod. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Returnerar läsarens tillstånd. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Returnerar schemainformationen som har tilldelats den aktuella noden. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Returnerar [XmlReaderSettings](../xmlreadersettings/)-objektet som används för att skapa denna [XmlReader](../xmlreader/)-instans. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Returnerar textvärdet för den aktuella noden. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Returnerar typen för den aktuella noden. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Returnerar det aktuella **xml:space**-omfånget. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Returnerar värdet på attributet med det angivna namnet. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Returnerar värdet på attributet med det angivna lokala namnet och namnrymds-URI. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Returnerar värdet på attributet med det angivna indexet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | När den överskuggas i en avledd klass hämtas värdet på attributet med det angivna indexet. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | När den överskuggas i en avledd klass hämtas värdet på attributet med det angivna [XmlReader::get_Name](../xmlreader/get_name/)-värdet. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | När den överskuggas i en avledd klass hämtas värdet på attributet med de angivna [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namn. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namn-token. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Anropar [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en start-tagg eller en tom element-tagg. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Anropar [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en start-tagg eller en tom element-tagg samt om [XmlReader::get_Name](../xmlreader/get_name/)-värdet för det hittade elementet matchar det givna argumentet. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Anropar [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en start-tagg eller en tom element-tagg samt om [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena för det hittade elementet matchar de givna strängarna. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Löser ett namnrymdsprefix i den aktuella elementets omfattning. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Flyttar till attributet med det angivna namnet. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Flyttar till attributet med det angivna lokala namnet och namnrymds-URI. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Flyttar till attributet med det angivna indexet. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Kontrollerar om den aktuella noden är ett innehåll (icke-blankstegstext, **CDATA**, **Element**, **EndElement**, **EntityReference** eller **EndEntity**) nod. Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller filslut. Den hoppar över noder av följande typ: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** eller **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Flyttar till elementet som innehåller den aktuella attributnoden. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Flyttar till det första attributet. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Flyttar till nästa attribut. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **bool** [Read](./read/)() override | Läser nästa nod från strömmen. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analyserar attributvärdet till en eller flera **[Text](../../system.text/)**, **EntityReference** eller **EndEntity**-noder. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser innehållet som ett objekt av den angivna typen. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser innehållet och returnerar de Base64-avkodade binära bytena. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser innehållet och returnerar de BinHex-avkodade binära bytena. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Läser textinnehållet på den aktuella positionen som ett [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Läser textinnehållet på den aktuella positionen som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Läser textinnehållet på den aktuella positionen som ett [DateTimeOffset](../../system/datetimeoffset/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Läser textinnehållet på den aktuella positionen som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Läser textinnehållet på den aktuella positionen som ett dubbelprecisions-flyttal. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Läser textinnehållet på den aktuella positionen som ett enkelprecisions-flyttal. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Läser textinnehållet på den aktuella positionen som ett 32-bitars heltal med tecken. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Läser textinnehållet på den aktuella positionen som ett 64-bitars heltal med tecken. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Läser textinnehållet på den aktuella positionen som ett [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Läser textinnehållet på den aktuella positionen som ett [String](../../system/string/)-objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser elementets innehåll som den begärda typen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan elementets innehåll som den begärda typen. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser elementet och avkodar Base64-innehållet. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser elementet och avkodar BinHex-innehållet. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Läser det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Läser det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Läser det aktuella elementet och returnerar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Läser det aktuella elementet och returnerar innehållet som ett dubbelprecisionstalet. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett dubbelprecisionstal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Läser det aktuella elementet och returnerar innehållet som ett enkelfloating-tal. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett enkelfloating-tal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Läser det aktuella elementet och returnerar innehållet som ett 32-bits signed-tal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett 32-bits signed-tal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Läser det aktuella elementet och returnerar innehållet som ett 64-bits signed-tal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett 64-bits signed-tal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Läser det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Läser det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Läser ett enbart-text-element. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett mer enkelt sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Kontrollerar att [XmlReader::get_Name](../xmlreader/get_name/)-värdet för det funna elementet matchar den givna strängen innan ett enbart-text-element läses. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett mer enkelt sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena för det funna elementet matchar de givna strängarna innan ett enbart-text-element läses. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett mer enkelt sätt att hantera denna operation. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Kontrollerar att den aktuella innehållsnoden är en sluttagg och avancerar läsaren till nästa nod. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | När den åsidosätts i en härledd klass läser den allt innehåll, inklusive markup, som en sträng. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | När den åsidosätts i en härledd klass läser den innehållet, inklusive markup, som representerar denna nod och alla dess barn. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Kontrollerar att den aktuella noden är ett element och avancerar läsaren till nästa nod. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med det givna [XmlReader::get_Name](../xmlreader/get_name/)-värdet och avancerar läsaren till nästa nod. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med de givna [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena och avancerar läsaren till nästa nod. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Läser innehållet i ett element eller textnod som en sträng. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Returnerar en ny [XmlReader](../xmlreader/)-instans som kan användas för att läsa den aktuella noden och alla dess undernoder. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Avancerar [XmlReader](../xmlreader/) till nästa underliggande element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Avancerar [XmlReader](../xmlreader/) till nästa underliggande element med det angivna lokala namnet och namnrymdens URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Läser tills ett element med det angivna kvalificerade namnet hittas. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Läser tills ett element med det angivna lokala namnet och namnrymdens URI hittas. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Avancerar [XmlReader](../xmlreader/) till nästa syskon-element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Avancerar [XmlReader](../xmlreader/) till nästa syskon-element med det angivna lokala namnet och namnrymdens URI. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Läser stora textströmmar inbäddade i ett XML-dokument. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetypobjekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [ResolveEntity](./resolveentity/)() override | Löser enhetsreferensen för **EntityReference**-noder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n'te mallargumentet till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Skip](./skip/)() override | Hoppar över barnnoderna för den aktuella noden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning av C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Skapar en instans av klassen [XmlNodeReader](./) med den angivna [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för delad pekare till en instans av denna klass. |
## Anmärkningar

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Wrappa alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se även

* Klass [XmlReader](../xmlreader/)
* Klass [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)