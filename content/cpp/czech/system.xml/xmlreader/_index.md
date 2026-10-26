---
title: XmlReader
second_title: Aspose.Slides pro C++ - reference API
description: Představuje čtečku, která poskytuje rychlý, bez vyrovnávací paměti, pouze dopředný přístup k XML datům.
type: docs
weight: 430
url: /cs/system.xml/xmlreader/
---
## XmlReader třída

Representuje čtečku, která poskytuje rychlý, neukládaný, pouze dopředný přístup k XML datům.

```cpp
class XmlReader : public System::IDisposable
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Close](./close/)() | Při přepsání v odvozené třídě změní [XmlReader::get_ReadState](./get_readstate/) na [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](./) se zadaným URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného URI, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného proudu s výchozím nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](./) se zadaným proudem a nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného proudu, základního URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného proudu, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného textového čtečky. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného textového čtečky a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného textového čtečky, nastavení a základního URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného textového čtečky, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Vytvoří novou instanci [XmlReader](./) pomocí zadaného XML čtečky a nastavení. |
| void [Dispose](./dispose/)() override | Uvolní veškeré prostředky používané aktuální instancí třídy [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | Při přepsání v odvozené třídě získá počet atributů na aktuálním uzlu. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Při přepsání v odvozené třídě získá základní URI aktuálního uzlu. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Vrací hodnotu indikující, zda [XmlReader](./) implementuje metody pro čtení binárního obsahu. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Vrací hodnotu indikující, zda [XmlReader](./) implementuje metodu [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Vrací hodnotu indikující, zda tento čtečka může analyzovat a rozpoznávat entity. |
| virtual **int32_t** [get_Depth](./get_depth/)() | Při přepsání v odvozené třídě získá hloubku aktuálního uzlu v XML dokumentu. |
| virtual **bool** [get_EOF](./get_eof/)() | Při přepsání v odvozené třídě získá hodnotu indikující, zda je čtečka umístěna na konci proudu. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Vrací hodnotu indikující, zda aktuální uzel má nějaké atributy. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | Při přepsání v odvozené třídě získá hodnotu indikující, zda aktuální uzel může mít hodnotu [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | Při přepsání v odvozené třídě získá hodnotu indikující, zda je aktuální uzel atribut, který byl vygenerován z výchozí hodnoty definované v DTD nebo schématu. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Při přepsání v odvozené třídě získá hodnotu indikující, zda je aktuální uzel prázdný prvek (například **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Při přepsání v odvozené třídě získá lokální název aktuálního uzlu. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Při přepsání v odvozené třídě získá kvalifikovaný název aktuálního uzlu. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Při přepsání v odvozené třídě získá URI jmenného prostoru (jak je definováno ve specifikaci W3C Namespace) uzlu, na kterém je čtečka umístěna. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Při přepsání v odvozené třídě získá [XmlNameTable](../xmlnametable/) spojený s touto implementací. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Při přepsání v odvozené třídě získá typ aktuálního uzlu. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Při přepsání v odvozené třídě získá prefix jmenného prostoru spojený s aktuálním uzlem. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | Při přepsání v odvozené třídě získá znak uvozovek používaný k ohraničení hodnoty atributového uzlu. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | Při přepsání v odvozené třídě získá stav čtečky. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Vrací objekt [XmlReaderSettings](../xmlreadersettings/) použitý k vytvoření této instance [XmlReader](./). |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Při přepsání v odvozené třídě získá textovou hodnotu aktuálního uzlu. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Vrací typ aktuálního uzlu. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Při přepsání v odvozené třídě získá aktuální rozsah **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Při přepsání v odvozené třídě získá aktuální rozsah **xml:space**. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | Při přepsání v odvozené třídě získá hodnotu atributu se zadaným indexem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | Při přepsání v odvozené třídě získá hodnotu atributu se zadaným indexem. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Vrací hodnotu indikující, zda je řetězcový argument platným názvem XML. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Vrací hodnotu indikující, zda je řetězcový argument platným tokenem názvu XML. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Volá [XmlReader::MoveToContent](./movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Volá [XmlReader::MoveToContent](./movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku a zda hodnota [XmlReader::get_Name](./get_name/) nalezeného prvku odpovídá zadanému argumentu. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Volá [XmlReader::MoveToContent](./movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku a zda hodnoty [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/) nalezeného prvku odpovídají zadaným řetězcům. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | Při přepsání v odvozené třídě rozřeší prefix jmenného prostoru v rozsahu aktuálního elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | Při přepsání v odvozené třídě přejde na atribut se zadanou hodnotou [XmlReader::get_Name](./get_name/). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Při přepsání v odvozené třídě přejde na atribut se zadanými hodnotami [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | Při přepsání v odvozené třídě přejde na atribut se zadaným indexem. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Kontroluje, zda je aktuální uzel obsahovým (nebílový text, **CDATA**, **Element**, **EndElement**, **EntityReference**, nebo **EndEntity**) uzlem. Pokud uzel není obsahovým, čtečka přeskočí na další obsahový uzel nebo konec souboru. Přeskakuje uzly následujícího typu: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, nebo **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | Při přepsání v odvozené třídě přejde na element, který obsahuje aktuální uzel atributu. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Při přepsání v odvozené třídě přejde na první atribut. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Při přepsání v odvozené třídě přejde na další atribut. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Nezkopíruje nic, opravdu, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Nezkopíruje nic, opravdu, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| virtual **bool** [Read](./read/)() | Při přepsání v odvozené třídě načte další uzel z proudu. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | Při přepsání v odvozené třídě parsuje hodnotu atributu do jednoho nebo více uzlů **[Text](../../system.text/)**, **EntityReference** nebo **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah jako objekt typu určeného. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Načte obsah a vrátí binární bajty dekódované z Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Načte obsah a vrátí binární bajty dekódované z **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Načte textový obsah na aktuální pozici jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Načte textový obsah na aktuální pozici jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Načte textový obsah na aktuální pozici jako objekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Načte textový obsah na aktuální pozici jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Načte textový obsah na aktuální pozici jako číslo s dvojitou přesností s plovoucí řádovou čárkou. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Načte textový obsah na aktuální pozici jako číslo s jednoduchou přesností s plovoucí řádovou čárkou. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Načte textový obsah na aktuální pozici jako 32bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Načte textový obsah na aktuální pozici jako 64bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Načte textový obsah na aktuální pozici jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Načte textový obsah na aktuální pozici jako objekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah elementu jako požadovaný typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte obsah elementu jako požadovaný typ. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Načte element a dekóduje obsah **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Načte element a dekóduje obsah **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Načte aktuální element a vrátí jeho obsah jako objekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako objekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Načte aktuální element a vrátí jeho obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Načte aktuální element a vrátí jeho obsah jako objekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Načte aktuální element a vrátí jeho obsah jako číslo s dvojitou přesností s plovoucí řádovou čárkou. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako číslo s dvojitou přesností s plovoucí řádovou čárkou. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Načte aktuální element a vrátí jeho obsah jako číslo s jednoduchou přesností s plovoucí řádovou čárkou. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako číslo s jednoduchou přesností s plovoucí řádovou čárkou. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Načte aktuální element a vrátí jeho obsah jako 32bitové celé číslo se znaménkem. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako 32bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Načte aktuální element a vrátí jeho obsah jako 64bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako 64bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Načte aktuální element a vrátí jeho obsah jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Načte aktuální element a vrátí jeho obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí jeho obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Načte element pouze s textem. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Zkontroluje, že hodnota [XmlReader::get_Name](./get_name/) nalezeného elementu odpovídá zadanému řetězci, než načte element pouze s textem. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že hodnoty [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům, než načte element pouze s textem. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual void [ReadEndElement](./readendelement/)() | Zkontroluje, že aktuální uzel obsahu je uzavírací značka, a posune čtečku na následující uzel. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | Při přepsání v odvozené třídě načte celý obsah, včetně značek, jako řetězec. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | Při přepsání v odvozené třídě načte obsah, včetně značek, představující tento uzel a všechny jeho potomky. |
| virtual void [ReadStartElement](./readstartelement/)() | Zkontroluje, že aktuální uzel je element, a posune čtečku na následující uzel. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Zkontroluje, že aktuální uzel obsahu je element s danou hodnotou [XmlReader::get_Name](./get_name/) a posune čtečku na následující uzel. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že aktuální uzel obsahu je element s danými hodnotami [XmlReader::get_LocalName](./get_localname/) a [XmlReader::get_NamespaceURI](./get_namespaceuri/) a posune čtečku na následující uzel. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Při přepsání v odvozené třídě načte obsah elementu nebo textového uzlu jako řetězec. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Vrátí novou instanci [XmlReader](./), která může být použita k načtení aktuálního uzlu a všech jeho potomků. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Posune [XmlReader](./) na následující podřízený element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](./) na následující podřízený element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Načte, dokud není nalezen element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Načte, dokud není nalezen element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Posune [XmlReader](./) na následující sourozenecký element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](./) na následující sourozenecký element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Načte velké textové proudy vložené v XML dokumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnoty s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [ResolveEntity](./resolveentity/)() | Při přepsání v odvozené třídě vyřeší odkaz entity pro uzly **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Skip](./skip/)() | Přeskočí potomky aktuálního uzlu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převést vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)