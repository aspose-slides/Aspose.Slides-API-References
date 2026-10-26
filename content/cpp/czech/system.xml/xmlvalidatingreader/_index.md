---
title: XmlValidatingReader
second_title: Aspose.Slides pro C++ API referenční příručka
description: Reprezentuje čtečku, která poskytuje validaci pomocí definice typu dokumentu (DTD), schématu XML-Data Reduced (XDR) a jazyka definice XML schématu (XSD).
type: docs
weight: 547
url: /cs/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader třída

Představuje čtečku, která poskytuje definici typu dokumentu (DTD), schéma XML-Data Reduced (XDR) a definici jazyka XML [Schema](../../system.xml.schema/) (XSD) pro validaci.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Close](./close/)() override | Změní [XmlReader::get_ReadState](../xmlreader/get_readstate/) na Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) se zadaným URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného URI, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného streamu s výchozím nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) se zadaným streamem a nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného streamu, základního URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného streamu, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí zadaného textového čtečky. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného textového čtečky a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného textového čtečky, nastavení a základního URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného textového čtečky, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Vytvoří novou instanci [XmlReader](../xmlreader/) použitím zadaného XML čtečky a nastavení. |
| void [Dispose](../xmlreader/dispose/)() override | Uvolní všechny prostředky používané aktuální instancí třídy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Vrací počet atributů na aktuálním uzlu. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Vrací základní URI aktuálního uzlu. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Vrací hodnotu označující, zda [XmlValidatingReader](./) implementuje metody pro čtení binárního obsahu. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Vrací hodnotu označující, zda [XmlReader](../xmlreader/) implementuje metodu [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Vrací hodnotu označující, zda tento čtečka může analyzovat a řešit entity. |
| **int32_t** [get_Depth](./get_depth/)() override | Vrací hloubku aktuálního uzlu v XML dokumentu. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Vrací atribut kódování pro dokument. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Vrací hodnotu, která určuje, jak čtečka zachází s entitami. |
| **bool** [get_EOF](./get_eof/)() override | Vrací hodnotu označující, zda je čtečka umístěna na konci streamu. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Vrací hodnotu označující, zda má aktuální uzel nějaké atributy. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Vrací hodnotu označující, zda může mít aktuální uzel [XmlValidatingReader::get_Value](./get_value/) jiný než [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Vrací hodnotu označující, zda je aktuální uzel atributem, který byl vygenerován z výchozí hodnoty definované v definici typu dokumentu (DTD) nebo schématu. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Vrací hodnotu označující, zda je aktuální uzel prázdným elementem (například **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Vrací aktuální číslo řádku. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Vrací aktuální pozici řádku. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Vrací lokální název aktuálního uzlu. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrací kvalifikovaný název aktuálního uzlu. |
| **bool** [get_Namespaces](./get_namespaces/)() | Vrací hodnotu označující, zda použít podporu jmenných prostorů. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Vrací Uniform Resource Identifier (URI) jmenného prostoru (jak je definováno ve specifikaci World Wide [Web](../../system.web/) Consortium (W3C) Namespace), uzlu, na kterém je čtečka umístěna. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Vrací [XmlNameTable](../xmlnametable/) spojený s touto implementací. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Vrací typ aktuálního uzlu. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Vrací prefix jmenného prostoru spojený s aktuálním uzlem. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Vrací znak uvozovek použitý k ohraničení hodnoty atributu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Vrací [XmlReader](../xmlreader/) použitý ke konstrukci tohoto [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Vrací stav čtečky. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Vrací XmlSchemaCollection k použití při validaci. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Vrací objekt typu schématu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Vrací objekt [XmlReaderSettings](../xmlreadersettings/) použitý k vytvoření této instance [XmlReader](../xmlreader/). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Vrací hodnotu označující typ validace, která má být provedena. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Vrací textovou hodnotu aktuálního uzlu. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Vrací typ aktuálního uzlu. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Vrací aktuální rozsah **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Vrací aktuální rozsah **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Vrací hodnotu atributu se zadaným názvem. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Vrací hodnotu atributu se zadaným lokálním názvem a Uniform Resource Identifier (URI) jmenného prostoru. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Vrací hodnotu atributu se zadaným indexem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Vrací hodnotu označující, zda třída může vracet informace o řádku. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Při přepsání v odvozené třídě získá hodnotu atributu se zadaným indexem. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Vrací hodnotu označující, zda je řetězcový argument platným XML názvem. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Vrací hodnotu označující, zda je řetězcový argument platným tokenem XML názvu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel startovacím tagem nebo prázdným elementem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel startovacím tagem nebo prázdným elementem a zda hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného elementu odpovídá zadanému argumentu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel startovacím tagem nebo prázdným elementem a zda hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání výrazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozřeší prefix jmenného prostoru v rozsahu aktuálního elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Přesune se na atribut se zadaným názvem. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Přesune se na atribut se zadaným lokálním názvem a Uniform Resource Identifier (URI) jmenného prostoru. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Přesune se na atribut se zadaným indexem. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Kontroluje, zda je aktuální uzel obsahovým (neprázdným textovým, **CDATA**, **Element**, **EndElement**, **EntityReference** nebo **EndEntity**) uzlem. Pokud uzel není obsahovým, čtečka přeskočí na další obsahový uzel nebo konec souboru. Přeskakuje uzly následujících typů: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** nebo **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Přesune se na element, který obsahuje aktuální atributový uzel. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Přesune se na první atribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Přesune se na další atribut. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| **bool** [Read](./read/)() override | Načte další uzel ze streamu. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Rozebere hodnotu atributu na jeden nebo více **[Text](../../system.text/)**, **EntityReference** nebo **EndEntity** uzlů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah jako objekt zadaného typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí Base64 dekódované binární bajty. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí BinHex dekódované binární bajty. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Načte textový obsah na aktuální pozici jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Načte textový obsah na aktuální pozici jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Načte textový obsah na aktuální pozici jako objekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Načte textový obsah na aktuální pozici jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Načte textový obsah na aktuální pozici jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Načte textový obsah na aktuální pozici jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Načte textový obsah na aktuální pozici jako 32-bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Načte textový obsah na aktuální pozici jako 64-bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Načte textový obsah na aktuální pozici jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Načte textový obsah na aktuální pozici jako objekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah elementu jako požadovaný typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte obsah elementu jako požadovaný typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte element a dekóduje obsah Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte element a dekóduje obsah BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Načte aktuální element a vrátí jeho obsah jako objekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako objekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Načte aktuální element a vrátí jeho obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Načte aktuální element a vrátí jeho obsah jako objekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Načte aktuální element a vrátí jeho obsah jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Načte aktuální element a vrátí jeho obsah jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Načte aktuální element a vrátí jeho obsah jako 32-bitové celé číslo se znaménkem. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako 32-bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Načte aktuální element a vrátí jeho obsah jako 64-bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako 64-bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Načte aktuální element a vrátí jeho obsah jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Načte aktuální element a vrátí jeho obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, poté načte aktuální element a vrátí jeho obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Načte element pouze s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje jednodušší způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Zkontroluje, že hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného elementu odpovídá zadanému řetězci před načtením elementu pouze s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje jednodušší způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům před načtením elementu pouze s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje jednodušší způsob, jak tuto operaci provést. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Zkontroluje, že aktuální obsahový uzel je koncová značka, a posune čtečku na další uzel. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Při přepsání v odvozené třídě načte celý obsah, včetně značek, jako řetězec. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Při přepsání v odvozené třídě načte obsah, včetně značek, který představuje tento uzel a všechny jeho potomky. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Zkontroluje, že aktuální uzel je element, a posune čtečku na další uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Zkontroluje, že aktuální obsahový uzel je element s danou hodnotou [XmlReader::get_Name](../xmlreader/get_name/) a posune čtečku na další uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že aktuální obsahový uzel je element s danými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) a posune čtečku na další uzel. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Načte obsah elementu nebo textového uzlu jako řetězec. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Vrátí novou instanci [XmlReader](../xmlreader/), kterou lze použít k načtení aktuálního uzlu a všech jeho potomků. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na další podřízený element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na další podřízený element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Čte až do nalezení elementu se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Čte až do nalezení elementu se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na další sourozenecký element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na další sourozenecký element se zadaným lokálním názvem a URI jmenného prostoru. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Vrátí typ runtime pro zadaný typ definice XML [Schema](../../system.xml.schema/) (XSD). |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Načte velké proudy textu vložené do XML dokumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt hodnotového typu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| void [ResolveEntity](./resolveentity/)() override | Rozřeší referenci entity pro uzly **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Nastaví hodnotu určující, jak čtečka zachází s entitami. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Nastaví hodnotu určující, zda provést podporu jmenných prostor. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Nastaví hodnotu určující typ prováděné validace. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Nastaví [XmlResolver](../xmlresolver/) používaný k rozřešení externích odkazů na definice typů dokumentů (DTD) a umístění schémat. [XmlResolver](../xmlresolver/) se také používá k obsluze jakýchkoli importovaných nebo zahrnutých elementů nalezených v XML [Schema](../../system.xml.schema/) definicích (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Přeskočí potomky aktuálního uzlu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Přidá obslužnou rutinu události pro získávání informací o chybách validace definice typu dokumentu (DTD), schématu XML-Data Reduced (XDR) a schématu XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Odstraní obslužnou rutinu události pro získávání informací o chybách validace definice typu dokumentu (DTD), schématu XML-Data Reduced (XDR) a schématu XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Inicializuje novou instanci třídy [XmlValidatingReader](./), která validuje obsah vrácený z daného [XmlReader](../xmlreader/). |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializuje novou instanci třídy [XmlValidatingReader](./) se zadanými hodnotami. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializuje novou instanci třídy [XmlValidatingReader](./) se zadanými hodnotami. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Poznámky

Zastaralé
:   Tato třída je zastaralá. Doporučuje se použít třídu [XmlReaderSettings](../xmlreadersettings/) a metodu [XmlReader::Create](../xmlreader/create/) k vytvoření validujícího XML čtečky.
Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím. 

## Viz také

* Třída [XmlReader](../xmlreader/)
* Třída [IXmlLineInfo](../ixmllineinfo/)
* Třída [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)