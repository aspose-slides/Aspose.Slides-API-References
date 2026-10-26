---
title: XmlNodeReader
second_title: Aspose.Slides pro C++ – reference API
description: Představuje čtečku, která poskytuje rychlý, nekešovaný pouze dopředný přístup k XML datům v objektu XmlNode.
type: docs
weight: 365
url: /cs/system.xml/xmlnodereader/
---
## XmlNodeReader třída

Representuje čtečku, která poskytuje rychlý, nekešovaný přístup jen vpřed k XML datům v [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metody

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Mění [XmlNodeReader::get_ReadState](./get_readstate/) na [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) se specifikovaným URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného URI, nastavení a kontextových informací pro analýzu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného proudu s výchozími nastaveními. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) se specifikovaným proudem a nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) s použitím specifikovaného proudu, základního URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) s použitím specifikovaného proudu, nastavení a kontextových informací pro analýzu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného textového čtečky. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného textového čtečky a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného textového čtečky, nastavení a základního URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného textového čtečky, nastavení a kontextových informací pro analýzu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí specifikovaného XML čtečky a nastavení. |
| void [Dispose](../xmlreader/dispose/)() override | Uvolní všechny prostředky použité aktuální instancí třídy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Vrátí počet atributů na aktuálním uzlu. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Vrátí základní URI aktuálního uzlu. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Vrátí hodnotu určující, zda [XmlNodeReader](./) implementuje metody čtení binárního obsahu. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Vrátí hodnotu určující, zda [XmlReader](../xmlreader/) implementuje metodu [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Vrátí hodnotu určující, zda tento čtečka může analyzovat a řešit entity. |
| **int32_t** [get_Depth](./get_depth/)() override | Vrátí hloubku aktuálního uzlu v XML dokumentu. |
| **bool** [get_EOF](./get_eof/)() override | Vrátí hodnotu určující, zda je čtečka umístěna na konci proudu. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Vrátí hodnotu určující, zda má aktuální uzel nějaké atributy. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Vrátí hodnotu určující, zda může mít aktuální uzel hodnotu [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Vrátí hodnotu určující, zda je aktuální uzel atributem vygenerovaným z výchozí hodnoty definované ve DTD nebo schématu. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Vrátí hodnotu určující, zda je aktuální uzel prázdným elementem (například **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Vrátí lokální název aktuálního uzlu. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrátí kvalifikovaný název aktuálního uzlu. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Vrátí URI jmenného prostoru (definované ve specifikaci W3C Namespace) uzlu, na kterém je čtečka umístěna. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Vrátí [XmlNameTable](../xmlnametable/) spojený s touto implementací. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Vrátí typ aktuálního uzlu. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Vrátí prefix jmenného prostoru spojený s aktuálním uzlem. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Při přepsání v odvozené třídě získá znak uvozovek používaný k uzavření hodnoty atributového uzlu. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Vrátí stav čtečky. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Vrátí informace o schématu přiřazené aktuálnímu uzlu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Vrátí objekt [XmlReaderSettings](../xmlreadersettings/) použitý k vytvoření této instance [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Vrátí textovou hodnotu aktuálního uzlu. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Vrátí typ pro aktuální uzel. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Vrátí aktuální rozsah **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Vrátí aktuální rozsah **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Vrátí hodnotu atributu se zadaným názvem. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Vrátí hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Vrátí hodnotu atributu se zadaným indexem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Při přepsání v odvozené třídě získá hodnotu atributu se zadaným indexem. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Při přepsání v odvozené třídě získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Vrátí hodnotu určující, zda je řetězcový argument platným názvem XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Vrátí hodnotu určující, zda je řetězcový argument platným tokenem názvu XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel počáteční značkou nebo prázdnou elementovou značkou. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel počáteční značkou nebo prázdnou elementovou značkou a zda se hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného elementu shoduje s daným argumentem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel počáteční značkou nebo prázdnou elementovou značkou a zda se hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného elementu shodují s danými řetězci. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozřeší prefix jmenného prostoru v rozsahu aktuálního elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Přesune se na atribut se zadaným názvem. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Přesune se na atribut se zadaným lokálním názvem a URI jmenného prostoru. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Přesune se na atribut se zadaným indexem. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Kontroluje, zda je aktuální uzel obsahovým (ne-bílým textem, **CDATA**, **Element**, **EndElement**, **EntityReference** nebo **EndEntity**) uzlem. Pokud uzel není obsahový, čtečka přeskakuje na další obsahový uzel nebo na konec souboru. Přeskakuje uzly následujících typů: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** nebo **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Přesune se na element, který obsahuje aktuální atributový uzel. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Přesune se na první atribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Přesune se na následující atribut. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| **bool** [Read](./read/)() override | Načte další uzel z proudu. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analyzuje hodnotu atributu na jeden nebo více uzlů **[Text](../../system.text/)**, **EntityReference** nebo **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah jako objekt specifikovaného typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí binární bajty dekódované z Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí binární bajty dekódované z BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Načte textový obsah na aktuální pozici jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Načte textový obsah na aktuální pozici jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Načte textový obsah na aktuální pozici jako objekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Načte textový obsah na aktuální pozici jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Načte textový obsah na aktuální pozici jako číslo s dvojitou přesností (double). |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Načte textový obsah na aktuální pozici jako číslo s jednoduchou přesností (float). |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Načte textový obsah na aktuální pozici jako 32bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Načte textový obsah na aktuální pozici jako 64bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Načte textový obsah na aktuální pozici jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Načte textový obsah na aktuální pozici jako objekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah elementu jako požadovaný typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte obsah elementu jako požadovaný typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte element a dekóduje obsah Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte element a dekóduje obsah BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Načte aktuální element a vrátí obsah jako objekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako objekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Načte aktuální element a vrátí obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Načte aktuální element a vrátí obsah jako objekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Načte aktuální element a vrátí obsah jako číslo s dvojitou přesností (double). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako číslo s dvojitou přesností (double). |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Načte aktuální element a vrátí obsah jako číslo s jednoduchou přesností (float). |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako číslo s jednoduchou přesností (float). |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Načte aktuální element a vrátí obsah jako 32bitové celé číslo se znaménkem. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako 32bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Načte aktuální element a vrátí obsah jako 64bitové celé číslo se znaménkem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako 64bitové celé číslo se znaménkem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Načte aktuální element a vrátí obsah jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Načte aktuální element a vrátí obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že zadaný lokální název a URI jmenného prostoru odpovídají aktuálnímu elementu, a poté načte aktuální element a vrátí obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Načte element obsahující pouze text. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Zkontroluje, že hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného elementu odpovídá zadanému řetězci před načtením elementu pouze s textem. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům před načtením elementu pouze s textem. Doporučujeme však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Zkontroluje, že aktuální obsahový uzel je koncová značka, a posune čtečku na následující uzel. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Při přepsání v odvozené třídě načte celý obsah, včetně značkování, jako řetězec. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Při přepsání v odvozené třídě načte obsah, včetně značkování, představující tento uzel a všechny jeho potomky. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Zkontroluje, že aktuální uzel je element, a posune čtečku na následující uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Zkontroluje, že aktuální obsahový uzel je element s danou hodnotou [XmlReader::get_Name](../xmlreader/get_name/), a posune čtečku na následující uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Zkontroluje, že aktuální obsahový uzel je element s danými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/), a posune čtečku na následující uzel. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Načte obsah elementu nebo textového uzlu jako řetězec. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Vrátí novou instanci [XmlReader](../xmlreader/), kterou lze použít k načtení aktuálního uzlu a všech jeho descendantů. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující descendantní element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující descendantní element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Čte, dokud není nalezen element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Čte, dokud není nalezen element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující sourozenecký element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující sourozenecký element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Načte velké proudy textu vložené v XML dokumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt hodnotového typu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| void [ResolveEntity](./resolveentity/)() override | Rozřeší referenci entity pro uzly **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Skip](./skip/)() override | Přeskočí potomky aktuálního uzlu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Vytvoří instanci třídy [XmlNodeReader](./) pomocí zadaného [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefs

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Remarks

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předávání jako argument funkcím. 

## See Also

* Třída [XmlReader](../xmlreader/)
* Třída [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Obor názvů [System::Xml](../)
* Knihovna [Aspose.Slides](../../)