---
title: XmlTextReader
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Reprezentuje čtečku, která poskytuje rychlý, neukládaný, pouze dopředný přístup k XML datům.
type: docs
weight: 508
url: /cs/system.xml/xmltextreader/
---
## XmlTextReader třída


Representuje čtečku, která poskytuje rychlý, neukládaný, pouze dopředný přístup k XML datům.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Close](./close/)() override | Změní [XmlReader::get_ReadState](../xmlreader/get_readstate/) na **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) s určeným URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného URI, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného proudu s výchozím nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) s určeným proudem a nastavením. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného proudu, základního URI a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného proudu, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného textového čtečky. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného textového čtečky a nastavení. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného textového čtečky, nastavení a základního URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného textového čtečky, nastavení a kontextových informací pro parsování. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Vytvoří novou instanci [XmlReader](../xmlreader/) pomocí určeného XML čtečky a nastavení. |
| void [Dispose](../xmlreader/dispose/)() override | Uvolní všechny zdroje používané aktuální instancí třídy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Vrací počet atributů na aktuálním uzlu. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Vrací základní URI aktuálního uzlu. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Vrací hodnotu indikující, zda [XmlTextReader](./) implementuje metody pro čtení binárního obsahu. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Vrací hodnotu indikující, zda [XmlTextReader](./) implementuje metodu [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Vrací hodnotu indikující, zda tento čtečka může analyzovat a rozpoznávat entity. |
| **int32_t** [get_Depth](./get_depth/)() override | Vrací hloubku aktuálního uzlu v XML dokumentu. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Vrací výčet DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Vrací kódování dokumentu. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Vrací hodnotu, která určuje, jak čtečka zachází s entitami. |
| **bool** [get_EOF](./get_eof/)() override | Vrací hodnotu indikující, zda je čtečka umístěna na konci proudu. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Vrací hodnotu indikující, zda aktuální uzel má nějaké atributy. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Vrací hodnotu indikující, zda aktuální uzel může mít [XmlTextReader::get_Value](./get_value/) jiný než [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Vrací hodnotu indikující, zda je aktuální uzel atribut generovaný z výchozí hodnoty definované v DTD nebo schématu. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Vrací hodnotu indikující, zda je aktuální uzel prázdný prvek (například **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Vrací aktuální číslo řádku. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Vrací aktuální pozici řádku. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Vrací lokální název aktuálního uzlu. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrací kvalifikovaný název aktuálního uzlu. |
| **bool** [get_Namespaces](./get_namespaces/)() | Vrací hodnotu indikující, zda provádět podporu jmenných prostorů. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Vrací URI jmenného prostoru (jak je definováno ve specifikaci W3C Namespace) uzlu, na kterém je čtečka umístěna. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Vrací [XmlNameTable](../xmlnametable/) spojený s touto implementací. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Vrací typ aktuálního uzlu. |
| **bool** [get_Normalization](./get_normalization/)() | Vrací hodnotu indikující, zda normalizovat bílé znaky a hodnoty atributů. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Vrací předponu jmenného prostoru spojenou s aktuálním uzlem. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Vrací hodnotu indikující, zda povolit zpracování DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Vrací znak uvozovek používaný k ohraničení hodnoty uzlu atributu. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Vrací stav čtečky. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Vrací objekt [XmlReaderSettings](../xmlreadersettings/) použitý k vytvoření této instance [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Vrací textovou hodnotu aktuálního uzlu. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Vrací typ aktuálního uzlu. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Vrací hodnotu, která určuje, jak jsou bílé znaky zpracovány. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Získá aktuální rozsah **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Získá aktuální rozsah **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Vrací hodnotu atributu se zadaným názvem. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Vrací hodnotu atributu se zadaným lokálním názvem a URI jmenného prostoru. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Vrací hodnotu atributu se zadaným indexem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Vrací kolekci, která obsahuje všechny aktuálně platné jmenné prostory. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Vrací zbytek vyrovnaného XML. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Vrací hodnotu indikující, zda třída může vracet informace o řádcích. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Když je přepsáno v odvozené třídě, získá hodnotu atributu se zadaným indexem. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Když je přepsáno v odvozené třídě, získá hodnotu atributu se zadanou hodnotou [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Když je přepsáno v odvozené třídě, získá hodnotu atributu se zadanými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Vrací hodnotu indikující, zda je řetězcový argument platným XML názvem. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Vrací hodnotu indikující, zda je řetězcový argument platným tokenem XML názvu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku a zda hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného prvku odpovídá zadanému argumentu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Volá [XmlReader::MoveToContent](../xmlreader/movetocontent/) a testuje, zda je aktuální obsahový uzel úvodní značkou nebo značkou prázdného prvku a zda hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného prvku odpovídají zadaným řetězcům. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozřeší předponu jmenného prostoru v rozsahu aktuálního elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Přesune se na atribut se zadaným názvem. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Přesune se na atribut se zadaným lokálním názvem a URI jmenného prostoru. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Přesune se na atribut se zadaným indexem. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Kontroluje, zda je aktuální uzel obsahovým (nebílé textové, **CDATA**, **Element**, **EndElement**, **EntityReference** nebo **EndEntity**) uzlem. Pokud uzel není obsahovým, čtečka přeskočí na další obsahový uzel nebo konec souboru. Přeskakuje uzly následujícího typu: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** nebo **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Přesune se na element, který obsahuje aktuální uzel atributu. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Přesune se na první atribut. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Přesune se na další atribut. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| **bool** [Read](./read/)() override | Čte další uzel ze proudu. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Analyzuje hodnotu atributu do jednoho nebo více uzlů **[Text](../../system.text/)**, **EntityReference** nebo **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekóduje Base64 a vrací dekódované binární bajty. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekóduje **BinHex** a vrací dekódované binární bajty. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Načte textový obsah prvku do znakové vyrovnávací paměti. Tato metoda je určena pro čtení velkých toků vloženého textu voláním po sobě. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah jako objekt zadaného typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí binární bajty dekódované z **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte obsah a vrátí binární bajty dekódované z **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Načte textový obsah na aktuální pozici jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Načte textový obsah na aktuální pozici jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Načte textový obsah na aktuální pozici jako objekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Načte textový obsah na aktuální pozici jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Načte textový obsah na aktuální pozici jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Načte textový obsah na aktuální pozici jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Načte textový obsah na aktuální pozici jako 32bitové podepsané celé číslo. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Načte textový obsah na aktuální pozici jako 64bitové podepsané celé číslo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Načte textový obsah na aktuální pozici jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Načte textový obsah na aktuální pozici jako objekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Načte obsah prvku jako požadovaný typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte obsah prvku jako požadovaný typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte prvek a dekóduje obsah Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Načte prvek a dekóduje obsah **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Načte aktuální prvek a vrátí obsah jako objekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako objekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Načte aktuální prvek a vrátí obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako objekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Načte aktuální prvek a vrátí obsah jako objekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako objekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Načte aktuální prvek a vrátí obsah jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako číslo s dvojitou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Načte aktuální prvek a vrátí obsah jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako číslo s jednoduchou přesností s plovoucí desetinnou čárkou. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Načte aktuální prvek a vrátí obsah jako 32bitové podepsané celé číslo. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako 32bitové podepsané celé číslo. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Načte aktuální prvek a vrátí obsah jako 64bitové podepsané celé číslo. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako 64bitové podepsané celé číslo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Načte aktuální prvek a vrátí obsah jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Načte aktuální prvek a vrátí obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že zadaný lokální název a URI jmenného prostoru se shoduje s aktuálním prvkem, a poté načte aktuální prvek a vrátí obsah jako objekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Načte element jen s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Ověří, že hodnota [XmlReader::get_Name](../xmlreader/get_name/) nalezeného elementu odpovídá zadanému řetězci před načtením elementu jen s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že hodnoty [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) nalezeného elementu odpovídají zadanym řetězcům před načtením elementu jen s textem. Doporučuje se však použít metodu [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), protože poskytuje přímější způsob, jak tuto operaci provést. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Ověří, že aktuální uzel obsahu je koncová značka, a posune čtečku na následující uzel. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Když je v odvozené třídě přepsáno, načte celý obsah, včetně značek, jako řetězec. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Když je v odvozené třídě přepsáno, načte obsah, včetně značek, představující tento uzel a všechny jeho potomky. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Ověří, že aktuální uzel je element, a posune čtečku na následující uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Ověří, že aktuální uzel obsahu je element s danou hodnotou [XmlReader::get_Name](../xmlreader/get_name/), a posune čtečku na další uzel. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Ověří, že aktuální uzel obsahu je element s danými hodnotami [XmlReader::get_LocalName](../xmlreader/get_localname/) a [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/), a posune čtečku na další uzel. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Načte obsah elementu nebo textového uzlu jako řetězec. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Vrátí novou instanci [XmlReader](../xmlreader/), kterou lze použít k načtení aktuálního uzlu a všech jeho podřízených uzlů. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující podřízený element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující podřízený element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Čte, dokud není nalezen element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Čte, dokud není nalezen element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující sourozenecký element se zadaným kvalifikovaným názvem. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Posune [XmlReader](../xmlreader/) na následující sourozenecký element se zadaným lokálním názvem a URI jmenného prostoru. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Načte velké toky textu vložené v XML dokumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| void [ResetState](./resetstate/)() | Resetuje stav čtečky na [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Rozřeší referenci entity pro uzly **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Nastavuje výčtový typ DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Nastavuje hodnotu, která určuje, jak čtečka zachází s entitami. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Nastavuje hodnotu, která určuje, zda povolit podporu jmenných prostorů. |
| void [set_Normalization](./set_normalization/)(**bool**) | Nastavuje hodnotu, která určuje, zda normalizovat bílé znaky a hodnoty atributů. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Nastavuje hodnotu, která určuje, zda povolit zpracování DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Nastavuje hodnotu, která určuje, jak se zachází s bílými znaky. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Nastavuje [XmlResolver](../xmlresolver/) používaný pro řešení DTD referencí. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech na slabý režim. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Skip](./skip/)() override | Přeskočí potomky aktuálního uzlu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Volat přímo nebo použít objekt strážení [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným proudem. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadanou URL a proudem. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným proudem a [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadanou URL, proudem a [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadanou URL a TextReader. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným TextReader a [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadanou URL, TextReader a [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným streamem, XmlNodeType a [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným řetězcem, XmlNodeType a [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným souborem. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicializuje novou instanci třídy [XmlTextReader](./) se zadaným souborem a [XmlNameTable](../xmlnametable/). |
|  virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |
## Poznámky



Je doporučeno použít třídu [XmlReader](../xmlreader/). 

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním assertion. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předávání jako argument funkcím. 

## Viz také

* Třída [XmlReader](../xmlreader/)
* Třída [IXmlLineInfo](../ixmllineinfo/)
* Třída [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)