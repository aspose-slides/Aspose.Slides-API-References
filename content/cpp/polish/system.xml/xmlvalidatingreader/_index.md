---
title: XmlValidatingReader
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Reprezentuje czytnik, który zapewnia walidację definicji typu dokumentu (DTD), schematu XML-Data Reduced (XDR) oraz języka definicji schematu XML (XSD).
type: docs
weight: 547
url: /pl/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader klasa

Reprezentuje czytnik, który zapewnia definicję typu dokumentu (DTD), schemat XML-Data Reduced (XDR) oraz walidację języka definicji XML [Schema](../../system.xml.schema/) (XSD) definition language (XSD) validation.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Zmienia [XmlReader::get_ReadState](../xmlreader/get_readstate/) na Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI, ustawień oraz informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia z domyślnymi ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym strumieniem i ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, bazowego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, ustawień oraz informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień i bazowego URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień oraz informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika XML i ustawień. |
| void [Dispose](../xmlreader/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Zwraca liczbę atrybutów w bieżącym węźle. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Zwraca bazowy URI bieżącego węzła. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Zwraca wartość wskazującą, czy [XmlValidatingReader](./) implementuje metody odczytu binarnej zawartości. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Zwraca wartość wskazującą, czy [XmlReader](../xmlreader/) implementuje metodę [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Zwraca wartość wskazującą, czy ten czytnik może parsować i rozwiązywać encje. |
| **int32_t** [get_Depth](./get_depth/)() override | Zwraca głębokość bieżącego węzła w dokumencie XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Zwraca atrybut kodowania dokumentu. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Zwraca wartość określającą, jak czytnik obsługuje encje. |
| **bool** [get_EOF](./get_eof/)() override | Zwraca wartość wskazującą, czy czytnik jest położony na końcu strumienia. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Zwraca wartość wskazującą, czy bieżący węzeł ma jakieś atrybuty. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Zwraca wartość wskazującą, czy bieżący węzeł może mieć [XmlValidatingReader::get_Value](./get_value/) inny niż [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest atrybutem wygenerowanym z wartości domyślnej zdefiniowanej w definicji typu dokumentu (DTD) lub schemacie. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest pustym elementem (np. **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Zwraca bieżący numer linii. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Zwraca bieżącą pozycję w linii. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Zwraca lokalną nazwę bieżącego węzła. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca kwalifikowaną nazwę bieżącego węzła. |
| **bool** [get_Namespaces](./get_namespaces/)() | Zwraca wartość wskazującą, czy włączyć obsługę przestrzeni nazw. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Zwraca identyfikator URI przestrzeni nazw (zgodnie z definicją konsorcjum World Wide [Web](../../system.web/) (W3C) specyfikacji Namespace) węzła, na którym znajduje się czytnik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Zwraca [XmlNameTable](../xmlnametable/) powiązany z tą implementacją. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Zwraca typ bieżącego węzła. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Zwraca prefiks przestrzeni nazw powiązany z bieżącym węzłem. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Zwraca znak cudzysłowu używany do otaczania wartości węzła atrybutu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Zwraca [XmlReader](../xmlreader/) używany do konstrukcji tego [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Zwraca stan czytnika. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Zwraca informacje o schemacie przypisane do bieżącego węzła w wyniku walidacji schematu. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Zwraca XmlSchemaCollection do użycia przy walidacji. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Zwraca obiekt typu schematu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Zwraca obiekt [XmlReaderSettings](../xmlreadersettings/) użyty do utworzenia tej instancji [XmlReader](../xmlreader/). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Zwraca wartość wskazującą typ walidacji do wykonania. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Zwraca wartość tekstową bieżącego węzła. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Zwraca typ bieżącego węzła. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Zwraca bieżący zakres **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Zwraca bieżący zakres **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Zwraca wartość atrybutu o określonej nazwie. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Zwraca wartość atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Zwraca wartość atrybutu o określonym indeksie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Zwraca wartość wskazującą, czy klasa może zwrócić informacje o linii. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Kiedy zostanie nadpisane w klasie pochodnej, pobiera wartość atrybutu o określonym indeksie. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Kiedy zostanie nadpisane w klasie pochodnej, pobiera wartość atrybutu o określonej wartości [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Kiedy zostanie nadpisane w klasie pochodnej, pobiera wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłową nazwą XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłowym tokenem nazwy XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i testuje, czy bieżący węzeł treści jest tagiem startowym lub pustym elementem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i testuje, czy bieżący węzeł treści jest tagiem startowym lub pustym elementem oraz czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu pasuje do podanego argumentu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i testuje, czy bieżący węzeł treści jest tagiem startowym lub pustym elementem oraz czy wartości [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) znalezionego elementu pasują do podanych łańcuchów. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Przechodzi do atrybutu o określonej nazwie. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Przechodzi do atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Przechodzi do atrybutu o określonym indeksie. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Sprawdza, czy bieżący węzeł jest węzłem treści (tekst niebiałych znaków, **CDATA**, **Element**, **EndElement**, **EntityReference** lub **EndEntity**). Jeśli węzeł nie jest węzłem treści, czytnik pomija go i przechodzi do następnego węzła treści lub końca pliku. Pomija węzły następujących typów: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** lub **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Przechodzi do elementu zawierającego bieżący węzeł atrybutu. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Przechodzi do pierwszego atrybutu. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Przechodzi do następnego atrybutu. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia tworzenie kopii podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia tworzenie kopii podklas. |
| **bool** [Read](./read/)() override | Odczytuje następny węzeł ze strumienia. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parsuje wartość atrybutu do jednego lub więcej węzłów **[Text](../../system.text/)**, **EntityReference** lub **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość jako obiekt określonego typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca binarne bajty zdekodowane z Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca binarne bajty zdekodowane z BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje zawartość elementu jako żądany typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje zawartość elementu jako żądany typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Odczytuje bieżący element i zwraca zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Odczytuje bieżący element i zwraca zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Odczytuje bieżący element i zwraca zawartość jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Odczytuje element zawierający wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Sprawdza, czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu odpowiada podanemu ciągowi przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) elementu znalezionego odpowiadają podanym ciągom przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Sprawdza, czy bieżący węzeł zawartości jest tagiem zamykającym i przesuwa czytnik do następnego węzła. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Gdy jest przesłonięta w klasie pochodnej, odczytuje całą zawartość, włącznie ze znacznikami, jako ciąg znaków. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Gdy jest przesłonięta w klasie pochodnej, odczytuje zawartość, włącznie ze znacznikami, reprezentującą ten węzeł i wszystkie jego potomki. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanej wartości [XmlReader::get_Name](../xmlreader/get_name/) i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) i przesuwa czytnik do następnego węzła. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Odczytuje zawartość elementu lub węzła tekstowego jako ciąg znaków. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Zwraca nową instancję [XmlReader](../xmlreader/), którą można użyć do odczytania bieżącego węzła oraz wszystkich jego potomków. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o podanej nazwie kwalifikowanej. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Czyta aż zostanie znaleziony element o podanej nazwie kwalifikowanej. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Czyta aż zostanie znaleziony element o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o podanej nazwie kwalifikowanej. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Zwraca typ czasu wykonywania dla określonego typu języka definicji XML [Schema](../../system.xml.schema/) (XSD). |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Odczytuje duże strumienie tekstu osadzone w dokumencie XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych odwołań o podaną wartość. |
| void [ResolveEntity](./resolveentity/)() override | Rozwiązuje odwołanie encji dla węzłów **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Ustawia wartość określającą, jak czytnik obsługuje encje. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ustawia wartość określającą, czy włączyć obsługę przestrzeni nazw. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Ustawia wartość określającą typ przeprowadzanej walidacji. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ustawia [XmlResolver](../xmlresolver/) używany do rozwiązywania odwołań do zewnętrznych definicji typu dokumentu (DTD) i lokalizacji schematów. [XmlResolver](../xmlresolver/) jest również używany do obsługi elementów import lub include znajdujących się w schematach języka definicji XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych odwołań. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | Pomija dzieci bieżącego węzła. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Dodaje obsługę zdarzenia odbierającego informacje o błędach walidacji definicji typu dokumentu (DTD), schematu XML-Data Reduced (XDR) oraz schematu języka definicji XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Usuwa obsługę zdarzenia odbierającego informacje o błędach walidacji definicji typu dokumentu (DTD), schematu XML-Data Reduced (XDR) oraz schematu języka definicji XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | Inicjalizuje nową instancję klasy [XmlValidatingReader](./), która waliduje zawartość zwróconą z podanego [XmlReader](../xmlreader/). |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicjalizuje nową instancję klasy [XmlValidatingReader](./) z określonymi wartościami. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicjalizuje nową instancję klasy [XmlValidatingReader](./) z określonymi wartościami. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Definicje typów

| Definicja | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |
## Uwagi

Przestarzałe
:   Ta klasa jest przestarzała. Zaleca się użycie klasy [XmlReaderSettings](../xmlreadersettings/) oraz metody [XmlReader::Create](../xmlreader/create/) do stworzenia walidującego czytnika XML.
Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/).  
Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji.  
Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i użyj tego wskaźnika, aby przekazać go do funkcji jako argument. 

## Zobacz także

* Klasa [XmlReader](../xmlreader/)
* Klasa [IXmlLineInfo](../ixmllineinfo/)
* Klasa [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)