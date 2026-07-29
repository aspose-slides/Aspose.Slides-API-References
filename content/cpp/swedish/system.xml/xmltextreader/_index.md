---
title: XmlTextReader
second_title: Aspose.Slides för C++ API-referens
description: Representerar en läsare som tillhandahåller snabb, icke-cachad, framåtriktad åtkomst till XML-data.
type: docs
weight: 508
url: /sv/system.xml/xmltextreader/
---
## XmlTextReader klass


Representerar en läsare som ger snabb, icke-cachad, framåt-endast åtkomst till XML-data.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Close](./close/)() override | Ändrar [XmlReader::get_ReadState](../xmlreader/get_readstate/) till **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med angiven URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna URI:n och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen, inställningarna och kontextinformationen för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen och standardinställningar. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen, bas-URI och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans med den angivna strömmen, inställningarna och kontextinformationen för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren, inställningarna och bas-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna textläsaren, inställningarna och kontextinformationen för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Skapar en ny [XmlReader](../xmlreader/)-instans genom att använda den angivna XML-läsaren och inställningarna. |
| void [Dispose](../xmlreader/dispose/)() override | Frigör alla resurser som används av den aktuella instansen av klassen [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Returnerar antalet attribut på den aktuella noden. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Returnerar bas-URI för den aktuella noden. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Returnerar ett värde som indikerar om [XmlTextReader](./) implementerar metoderna för binär innehålls läsning. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Returnerar ett värde som indikerar om [XmlTextReader](./) implementerar [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/)-metoden. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Returnerar ett värde som indikerar om denna läsare kan parsra och lösa entiteter. |
| **int32_t** [get_Depth](./get_depth/)() override | Returnerar djupet för den aktuella noden i XML-dokumentet. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Returnerar DtdProcessing-enumerationen. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Returnerar kodningen för dokumentet. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Returnerar ett värde som specificerar hur läsaren hanterar entiteter. |
| **bool** [get_EOF](./get_eof/)() override | Returnerar ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Returnerar ett värde som indikerar om den aktuella noden kan ha en [XmlTextReader::get_Value](./get_value/) annan än [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett attribut som genererats från standardvärdet definierat i DTD:n eller schemat. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Returnerar ett värde som indikerar om den aktuella noden är ett tomt element (till exempel **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Returnerar det aktuella radnumret. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Returnerar den aktuella radpositionen. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på den aktuella noden. |
| **bool** [get_Namespaces](./get_namespaces/)() | Returnerar ett värde som indikerar om namnrymdsstöd ska användas. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymdens URI (som definierat i W3C:s namnrymdsspecifikation) för den nod som läsaren är placerad på. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Returnerar [XmlNameTable](../xmlnametable/) associerad med denna implementering. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Returnerar typen för den aktuella noden. |
| **bool** [get_Normalization](./get_normalization/)() | Returnerar ett värde som indikerar om blanksteg och attributvärden ska normaliseras. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Returnerar namnrymdprefixet som är associerat med den aktuella noden. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Returnerar ett värde som indikerar om DTD-behandling ska tillåtas. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Returnerar citationstecknet som används för att omge värdet på ett attribut-nod. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Returnerar läsarens tillstånd. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Returnerar schemainformationen som har tilldelats den aktuella noden som resultat av schemavalidering. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Returnerar [XmlReaderSettings](../xmlreadersettings/)-objektet som användes för att skapa denna [XmlReader](../xmlreader/)-instans. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Returnerar textvärdet på den aktuella noden. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Returnerar typen för den aktuella noden. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Returnerar ett värde som specificerar hur blanksteg hanteras. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Returnerar det aktuella **xml:lang**-omfånget. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Returnerar det aktuella **xml:space**-omfånget. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Returnerar värdet på attributet med det angivna namnet. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Returnerar värdet på attributet med det angivna indexet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-[Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Returnerar en samling som innehåller alla namnrymder som för närvarande är i scope. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Returnerar resten av den buffrade XML-en. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C#-[System.Object.GetType()](../../system/object/gettype/)-anropet. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Returnerar ett värde som indikerar om klassen kan returnera radinformation. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | När den överskuggas i en derivatklass hämtas värdet på attributet med det angivna indexet. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | När den överskuggas i en derivatklass hämtas värdet på attributet med det angivna [XmlReader::get_Name](../xmlreader/get_name/)-värdet. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | När den överskuggas i en derivatklass hämtas värdet på attributet med de angivna [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namn. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namntoken. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Kallar på [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller tom elementtagg. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Kallar på [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller tom elementtagg samt om [XmlReader::get_Name](../xmlreader/get_name/)-värdet för det hittade elementet matchar det givna argumentet. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Kallar på [XmlReader::MoveToContent](../xmlreader/movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller tom elementtagg samt om [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena för det hittade elementet matchar de angivna strängarna. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Löser ett namnrymdsprefix i det aktuella elementets scope. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Flyttar till attributet med det angivna namnet. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Flyttar till attributet med det angivna lokala namnet och namnrymdens URI. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Flyttar till attributet med det angivna indexet. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Kontrollerar om den aktuella noden är en innehållsnod (icke-blankstegstext, **CDATA**, **Element**, **EndElement**, **EntityReference** eller **EndEntity**). Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller filslut. Den hoppar över noder av följande typer: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** eller **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Flyttar till elementet som innehåller den aktuella attributnoden. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Flyttar till det första attributet. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Flyttar till nästa attribut. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| **bool** [Read](./read/)() override | Läser nästa nod från strömmen. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Tolkar attributvärdet till en eller flera **[Text](../../system.text/)**, **EntityReference** eller **EndEntity**-noder. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Avkodar Base64 och returnerar de avkodade binära bytes. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Avkodar **BinHex** och returnerar de avkodade binära bytes. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Läser textinnehållet i ett element till en teckenbuffert. Denna metod är avsedd att läsa stora strömmar av inbäddad text genom att anropa den successivt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser innehållet som ett objekt av den angivna typen. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser innehållet och returnerar de **Base64** avkodade binära bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser innehållet och returnerar de **BinHex** avkodade binära bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Läser textinnehållet på den aktuella positionen som en [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Läser textinnehållet på den aktuella positionen som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Läser textinnehållet på den aktuella positionen som ett [DateTimeOffset](../../system/datetimeoffset/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Läser textinnehållet på den aktuella positionen som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Läser textinnehållet på den aktuella positionen som ett flyttal med dubbel precision. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Läser textinnehållet på den aktuella positionen som ett flyttal med enkel precision. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Läser textinnehållet på den aktuella positionen som ett 32-bitars signerat heltal. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Läser textinnehållet på den aktuella positionen som ett 64-bitars signerat heltal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Läser textinnehållet på den aktuella positionen som en [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Läser textinnehållet på den aktuella positionen som ett [String](../../system/string/)-objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser elementets innehåll som den begärda typen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, och läser sedan elementets innehåll som den begärda typen. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser elementet och avkodar Base64-innehållet. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Läser elementet och avkodar **BinHex**-innehållet. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Läser det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Läser det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Läser det aktuella elementet och returnerar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Läser det aktuella elementet och returnerar innehållet som ett flyttal med dubbel precision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett flyttal med dubbel precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Läser det aktuella elementet och returnerar innehållet som ett flyttal med enkel precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett flyttal med enkel precision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Läser det aktuella elementet och returnerar innehållet som ett 32-bitars signerat heltal. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett 32-bitars signerat heltal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Läser det aktuella elementet och returnerar innehållet som ett 64-bitars signerat heltal. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett 64-bitars signerat heltal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Läser det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Läser det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymds-URI:en matchar det för det aktuella elementet, läser sedan det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Läser ett element som bara innehåller text. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett enklare sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Kontrollerar att värdet [XmlReader::get_Name](../xmlreader/get_name/) för det hittade elementet matchar den angivna strängen innan ett endast-text-element läses. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett enklare sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att värdena [XmlReader::get_LocalName](../xmlreader/get_localname/) och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) för det hittade elementet matchar de givna strängarna innan ett endast-text-element läses. Det rekommenderas dock att använda metoden [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) istället, eftersom den ger ett enklare sätt att hantera denna operation. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Kontrollerar att den aktuella innehållsnoden är en sluttagg och flyttar läsaren till nästa nod. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | När den åsidosätts i en avledd klass läses allt innehåll, inklusive markup, som en sträng. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | När den åsidosätts i en avledd klass läses innehållet, inklusive markup, som representerar denna nod och alla dess undernoder. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Kontrollerar att den aktuella noden är ett element och flyttar läsaren till nästa nod. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med det angivna [XmlReader::get_Name](../xmlreader/get_name/)-värdet och flyttar läsaren till nästa nod. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med de angivna [XmlReader::get_LocalName](../xmlreader/get_localname/)- och [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/)-värdena och flyttar läsaren till nästa nod. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Läser innehållet i ett element eller en textnod som en sträng. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Returnerar en ny [XmlReader](../xmlreader/)-instans som kan användas för att läsa den aktuella noden och alla dess efterkommande. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Flyttar [XmlReader](../xmlreader/) till nästa underordnade element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XmlReader](../xmlreader/) till nästa underordnade element med det angivna lokala namnet och namnrymds-URI:n. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Läser tills ett element med det angivna kvalificerade namnet hittas. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Läser tills ett element med det angivna lokala namnet och namnrymds-URI:n hittas. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Flyttar [XmlReader](../xmlreader/) till nästa syskon-element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Flyttar [XmlReader](../xmlreader/) till nästa syskon-element med det angivna lokala namnet och namnrymds-URI:n. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Läser stora textströmmar som är inbäddade i ett XML-dokument. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknet med angivet värde. |
| void [ResetState](./resetstate/)() | Återställer läsarens tillstånd till [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Löser entitetsreferensen för **EntityReference**-noder. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Ställer in DtdProcessing-enumerationen. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Ställer in ett värde som anger hur läsaren hanterar enheter. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ställer in ett värde som anger om namnrymdsstöd ska användas. |
| void [set_Normalization](./set_normalization/)(**bool**) | Ställer in ett värde som anger om blanksteg och attributvärden ska normaliseras. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Ställer in ett värde som anger om DTD-behandling ska tillåtas. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Ställer in ett värde som anger hur blanksteg ska hanteras. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ställer in [XmlResolver](../xmlresolver/) som används för att lösa DTD-referenser. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Anger det n-te mallargumentet som en svag pekare (istället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Skip](./skip/)() override | Hoppar över barnnoderna för den aktuella noden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar C#-lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en och strömmen. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen och [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en, strömmen och [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en och TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna TextReader och [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna URL:en, TextReader och [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strömmen, XmlNodeType och [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna strängen, XmlNodeType och [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna filen. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initierar en ny instans av klassen [XmlTextReader](./) med den angivna filen och [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av den här klassen. |
## Anmärkningar



Det rekommenderas att använda klassen [XmlReader](../xmlreader/) istället. 

Objekt av den här klassen bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Inpaketera alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. 

## Se också

* Klass [XmlReader](../xmlreader/)
* Klass [IXmlLineInfo](../ixmllineinfo/)
* Klass [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)