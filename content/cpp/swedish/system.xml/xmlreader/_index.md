---
title: XmlReader
second_title: Aspose.Slides för C++ API-referens
description: Representerar en läsare som ger snabb, ej cachad, framåtriktad åtkomst till XML-data.
type: docs
weight: 430
url: /sv/system.xml/xmlreader/
---
## XmlReader klass

Representerar en läsare som ger snabb, icke-cachad, framåt-endast åtkomst till XML-data.

```cpp
class XmlReader : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [Close](./close/)() | När den åsidosätts i en avledd klass ändras [XmlReader::get_ReadState](./get_readstate/) till [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Skapar en ny [XmlReader](./)-instans med specificerad URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade URI:n och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade URI:n, inställningarna och kontextinformation för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Skapar en ny [XmlReader](./)-instans med den specificerade strömmen och standardinställningar. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](./)-instans med den specificerade strömmen och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](./)-instans med den specificerade strömmen, grund-URI och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](./)-instans med den specificerade strömmen, inställningarna och kontextinformation för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade textläsaren. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade textläsaren och inställningarna. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade textläsaren, inställningarna och grund-URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade textläsaren, inställningarna och kontextinformation för parsning. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Skapar en ny [XmlReader](./)-instans genom att använda den specificerade XML-läsaren och inställningarna. |
| void [Dispose](./dispose/)() override | Frigör alla resurser som används av den aktuella instansen av [XmlReader](./)-klassen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | När den åsidosätts i en avledd klass får den antalet attribut på den aktuella noden. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | När den åsidosätts i en avledd klass får den bas-URI:n för den aktuella noden. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Returnerar ett värde som indikerar om [XmlReader](./) implementerar metoderna för läsning av binärt innehåll. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Returnerar ett värde som indikerar om [XmlReader](./) implementerar [XmlReader::ReadValueChunk](./readvaluechunk/)-metoden. |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Returnerar ett värde som indikerar om denna läsare kan analysera och lösa upp entiteter. |
| virtual **int32_t** [get_Depth](./get_depth/)() | När den åsidosätts i en avledd klass får den djupet för den aktuella noden i XML-dokumentet. |
| virtual **bool** [get_EOF](./get_eof/)() | När den åsidosätts i en avledd klass får den ett värde som indikerar om läsaren är placerad i slutet av strömmen. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Returnerar ett värde som indikerar om den aktuella noden har några attribut. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | När den åsidosätts i en avledd klass får den ett värde som indikerar om den aktuella noden kan ha ett [XmlReader::get_Value](./get_value/)-värde. |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | När den åsidosätts i en avledd klass får den ett värde som indikerar om den aktuella noden är ett attribut som genererats från standardvärdet definierat i DTD eller schema. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | När den åsidosätts i en avledd klass får den ett värde som indikerar om den aktuella noden är ett tomt element (t.ex. **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | När den åsidosätts i en avledd klass får den det lokala namnet för den aktuella noden. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | När den åsidosätts i en avledd klass får den det kvalificerade namnet för den aktuella noden. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | När den åsidosätts i en avledd klass får den namnrymdens URI (enligt W3C:s namnrymdsspecifikation) för noden som läsaren är placerad på. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | När den åsidosätts i en avledd klass får den [XmlNameTable](../xmlnametable/) som är associerad med denna implementation. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | När den åsidosätts i en avledd klass får den typen för den aktuella noden. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | När den åsidosätts i en avledd klass får den namnrymdspräfixet som är associerat med den aktuella noden. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | När den åsidosätts i en avledd klass får den citattecknet som används för att omge värdet av ett attributnod. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | När den åsidosätts i en avledd klass får den läsarens tillstånd. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Returnerar schemainformationen som har tilldelats den aktuella noden som ett resultat av schemavalidering. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Returnerar [XmlReaderSettings](../xmlreadersettings/)-objektet som användes för att skapa denna [XmlReader](./)-instans. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | När den åsidosätts i en avledd klass får den textvärdet för den aktuella noden. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Returnerar typen för den aktuella noden. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | När den åsidosätts i en avledd klass får den det aktuella **xml:lang**-omfånget. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | När den åsidosätts i en avledd klass får den det aktuella **xml:space**-omfånget. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | När den åsidosätts i en avledd klass får den värdet på attributet med det angivna [XmlReader::get_Name](./get_name/)-värdet. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | När den åsidosätts i en avledd klass får den värdet på attributet med de angivna [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | När den åsidosätts i en avledd klass får den värdet på attributet med det angivna indexet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | När den åsidosätts i en avledd klass får den värdet på attributet med det angivna indexet. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | När den åsidosätts i en avledd klass får den värdet på attributet med det angivna [XmlReader::get_Name](./get_name/)-värdet. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | När den åsidosätts i en avledd klass får den värdet på attributet med de angivna [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namn. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Returnerar ett värde som indikerar om strängargumentet är ett giltigt XML-namntoken. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Anropar [XmlReader::MoveToContent](./movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Anropar [XmlReader::MoveToContent](./movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg och om [XmlReader::get_Name](./get_name/)-värdet för det hittade elementet matchar det givna argumentet. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Anropar [XmlReader::MoveToContent](./movetocontent/) och testar om den aktuella innehållsnoden är en starttagg eller en tom elementtagg samt om [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena för det hittade elementet matchar de givna strängarna. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | När den åsidosätts i en avledd klass löser den ett namnrymdspräfix i den aktuella elementets räckvidd. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | När den åsidosätts i en avledd klass flyttar den till attributet med det angivna [XmlReader::get_Name](./get_name/)-värdet. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | När den åsidosätts i en avledd klass flyttar den till attributet med de angivna [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | När den åsidosätts i en avledd klass flyttar den till attributet med det angivna indexet. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Kontrollerar om den aktuella noden är ett innehållsnod (icke-blankstegstext, **CDATA**, **Element**, **EndElement**, **EntityReference** eller **EndEntity**). Om noden inte är en innehållsnod hoppar läsaren fram till nästa innehållsnod eller slutet på filen. Den hoppar över noder av följande typer: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** eller **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | När den åsidosätts i en avledd klass flyttar den till elementet som innehåller den aktuella attributnoden. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | När den åsidosätts i en avledd klass flyttar den till det första attributet. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | När den åsidosätts i en avledd klass flyttar den till nästa attribut. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| virtual **bool** [Read](./read/)() | När den åsidosätts i en avledd klass läser den nästa nod från strömmen. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | När den åsidosätts i en avledd klass tolkar den attributvärdet till ett eller flera **[Text](../../system.text/)**, **EntityReference** eller **EndEntity**-noder. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser innehållet som ett objekt av den angivna typen. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Läser innehållet och returnerar de Base64-avkodade binära bytena. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Läser innehållet och returnerar de **BinHex**-avkodade binära bytena. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Läser textinnehållet på den aktuella positionen som en [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Läser textinnehållet vid den aktuella positionen som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Läser textinnehållet vid den aktuella positionen som ett [DateTimeOffset](../../system/datetimeoffset/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Läser textinnehållet vid den aktuella positionen som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Läser textinnehållet vid den aktuella positionen som ett dubbelprecisionsflyttal. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Läser textinnehållet vid den aktuella positionen som ett enkelprecisionsflyttal. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Läser textinnehållet vid den aktuella positionen som ett 32-bitssignerat heltal. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Läser textinnehållet vid den aktuella positionen som ett 64-bitssignerat heltal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Läser textinnehållet vid den aktuella positionen som ett [Object](../../system/object/)-objekt. |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Läser textinnehållet vid den aktuella positionen som ett [String](../../system/string/)-objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Läser elementets innehåll som den begärda typen. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan elementets innehåll som den begärda typen. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Läser elementet och avkodar **Base64**-innehållet. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Läser elementet och avkodar **BinHex**-innehållet. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Läser det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [Boolean](../../system/boolean/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Läser det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [DateTime](../../system/datetime/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Läser det aktuella elementet och returnerar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och återlämnar innehållet som ett [Decimal](../../system/decimal/)-objekt. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Läser det aktuella elementet och returnerar innehållet som ett dubbelprecisionsflyttal. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett dubbelprecisionsflyttal. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Läser det aktuella elementet och returnerar innehållet som ett enkelprecisionsflyttal. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett enkelprecisionsflyttal. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Läser det aktuella elementet och returnerar innehållet som ett 32-bitssignerat heltal. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett 32-bitssignerat heltal. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Läser det aktuella elementet och returnerar innehållet som ett 64-bitssignerat heltal. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett 64-bitssignerat heltal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Läser det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/)-objekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [Object](../../system/object/)-objekt. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Läser det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att det angivna lokala namnet och namnrymdens URI matchar det för det aktuella elementet, och läser sedan det aktuella elementet och returnerar innehållet som ett [String](../../system/string/)-objekt. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Läser ett endast text-element. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](./readelementcontentasstring/)-metoden istället, eftersom den ger ett mer direkt sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Kontrollerar att [XmlReader::get_Name](./get_name/)-värdet för det funna elementet matchar den givna strängen innan ett endast text-element läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](./readelementcontentasstring/)-metoden istället, eftersom den ger ett mer direkt sätt att hantera denna operation. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena för det funna elementet matchar de givna strängarna innan ett endast text-element läses. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](./readelementcontentasstring/)-metoden istället, eftersom den ger ett mer direkt sätt att hantera denna operation. |
| virtual void [ReadEndElement](./readendelement/)() | Kontrollerar att den aktuella innehållsnoden är en sluttagg och flyttar läsaren till nästa nod. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | När den åsidosätts i en avledd klass läser den allt innehåll, inklusive markup, som en sträng. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | När den åsidosätts i en avledd klass läser den innehållet, inklusive markup, som representerar denna nod och alla dess barn. |
| virtual void [ReadStartElement](./readstartelement/)() | Kontrollerar att den aktuella noden är ett element och flyttar läsaren till nästa nod. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med det givna [XmlReader::get_Name](./get_name/)-värdet och flyttar läsaren till nästa nod. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Kontrollerar att den aktuella innehållsnoden är ett element med de givna [XmlReader::get_LocalName](./get_localname/)- och [XmlReader::get_NamespaceURI](./get_namespaceuri/)-värdena och flyttar läsaren till nästa nod. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | När den åsidosätts i en avledd klass läser den innehållet i ett element eller en textnod som en sträng. Det rekommenderas dock att använda [XmlReader::ReadElementContentAsString](./readelementcontentasstring/)-metoden istället, eftersom den ger ett mer direkt sätt att hantera denna operation. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Returnerar en ny [XmlReader](./)-instans som kan användas för att läsa den aktuella noden och alla dess efterföljare. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Förflyttar [XmlReader](./) till nästa underordnade element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Förflyttar [XmlReader](./) till nästa underordnade element med det angivna lokala namnet och namnrymdens URI. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Läser tills ett element med det angivna kvalificerade namnet hittas. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Läser tills ett element med det angivna lokala namnet och namnrymdens URI hittas. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Förflyttar [XmlReader](./) till nästa syskon-element med det angivna kvalificerade namnet. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Förflyttar [XmlReader](./) till nästa syskon-element med det angivna lokala namnet och namnrymdens URI. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Läser stora textströmmar inbäddade i ett XML-dokument. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delat referensräknare med angivet värde. |
| virtual void [ResolveEntity](./resolveentity/)() | När den åsidosätts i en avledd klass löser den entitetsreferensen för **EntityReference**-noder. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [Skip](./skip/)() | Hoppar över barnen till den aktuella noden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | En alias för delad pekare till en instans av denna klass. |

## Se även

* Klass [IDisposable](../../system/idisposable/)
* Namnrymd [System::Xml](../)
* Bibliotek [Aspose.Slides](../../)