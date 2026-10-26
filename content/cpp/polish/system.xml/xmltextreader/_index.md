---
title: XmlTextReader
second_title: Odwołanie API Aspose.Slides dla C++
description: Reprezentuje czytnik zapewniający szybki, niebuforowany, jedynie w przód dostęp do danych XML.
type: docs
weight: 508
url: /pl/system.xml/xmltextreader/
---
## XmlTextReader klasa

Reprezentuje czytnik zapewniający szybki, niebuforowany, jedynie w przód dostęp do danych XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metody

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Zmienia [XmlReader::get_ReadState](../xmlreader/get_readstate/) na **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI, ustawień i informacji kontekstowych dla parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia z ustawieniami domyślnymi. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym strumieniem i ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, bazowego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, ustawień i informacji kontekstowych dla parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień i bazowego URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień i informacji kontekstowych dla parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika XML i ustawień. |
| void [Dispose](../xmlreader/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, łącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, łącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Zwraca liczbę atrybutów bieżącego węzła. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Zwraca bazowy URI bieżącego węzła. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Zwraca wartość wskazującą, czy [XmlTextReader](./) implementuje metody odczytu zawartości binarnej. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | Zwraca wartość wskazującą, czy [XmlTextReader](./) implementuje metodę [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Zwraca wartość wskazującą, czy ten czytnik może analizować i rozwiązywać encje. |
| **int32_t** [get_Depth](./get_depth/)() override | Zwraca głębokość bieżącego węzła w dokumencie XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Zwraca wyliczenie DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Zwraca kodowanie dokumentu. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Zwraca wartość określającą, jak czytnik obsługuje encje. |
| **bool** [get_EOF](./get_eof/)() override | Zwraca wartość wskazującą, czy czytnik znajduje się na końcu strumienia. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Zwraca wartość wskazującą, czy bieżący węzeł ma jakiekolwiek atrybuty. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Zwraca wartość wskazującą, czy bieżący węzeł może mieć [XmlTextReader::get_Value](./get_value/) inny niż [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest atrybutem wygenerowanym z wartości domyślnej określonej w DTD lub schemacie. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest pustym elementem (np. **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Zwraca bieżący numer wiersza. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Zwraca bieżącą pozycję wiersza. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Zwraca lokalną nazwę bieżącego węzła. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca kwalifikowaną nazwę bieżącego węzła. |
| **bool** [get_Namespaces](./get_namespaces/)() | Zwraca wartość wskazującą, czy włączyć obsługę przestrzeni nazw. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Zwraca URI przestrzeni nazw (zgodnie ze specyfikacją W3C Namespace) węzła, na którym znajduje się czytnik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Zwraca [XmlNameTable](../xmlnametable/) powiązany z tą implementacją. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Zwraca typ bieżącego węzła. |
| **bool** [get_Normalization](./get_normalization/)() | Zwraca wartość wskazującą, czy normalizować białe znaki i wartości atrybutów. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Zwraca prefiks przestrzeni nazw powiązany z bieżącym węzłem. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Zwraca wartość wskazującą, czy zezwolić na przetwarzanie DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Zwraca znak cudzysłowu używany do otaczania wartości węzła atrybutu. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Zwraca stan czytnika. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Zwraca informacje schematu przypisane do bieżącego węzła w wyniku walidacji schematu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Zwraca obiekt [XmlReaderSettings](../xmlreadersettings/) używany do stworzenia tej instancji [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Zwraca wartość tekstową bieżącego węzła. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Zwraca typ bieżącego węzła. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Zwraca wartość określającą, jak obsługiwane są białe znaki. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Zwraca bieżący zakres **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Zwraca bieżący zakres **xml:space**. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Zwraca wartość atrybutu o określonej nazwie. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Zwraca wartość atrybutu o określonej nazwie lokalnej i URI przestrzeni nazw. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Zwraca wartość atrybutu o określonym indeksie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Zwraca kolekcję zawierającą wszystkie aktualnie obowiązujące przestrzenie nazw. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Zwraca pozostałą część buforowanego XML. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | Zwraca wartość wskazującą, czy klasa może zwracać informacje o wierszu. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Gdy przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonym indeksie. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Gdy przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonej wartości [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Gdy przesłonięta w klasie pochodnej, pobiera wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłową nazwą XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłowym tokenem nazwy XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł treści jest tagiem początkowym lub pustym elementem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł treści jest tagiem początkowym lub pustym elementem oraz czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu pasuje do podanego argumentu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł treści jest tagiem początkowym lub pustym elementem oraz czy wartości [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) znalezionego elementu pasują do podanych ciągów. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów własnych. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Przechodzi do atrybutu o określonej nazwie. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Przechodzi do atrybutu o określonej nazwie lokalnej i URI przestrzeni nazw. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Przechodzi do atrybutu o określonym indeksie. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Sprawdza, czy bieżący węzeł jest węzłem treści (tekst niebiałej spacji, **CDATA**, **Element**, **EndElement**, **EntityReference** lub **EndEntity**). Jeśli węzeł nie jest węzłem treści, czytnik pomija go i przechodzi do następnego węzła treści lub końca pliku. Pomija węzły następujących typów: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** lub **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Przechodzi do elementu zawierającego bieżący węzeł atrybutu. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Przechodzi do pierwszego atrybutu. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Przechodzi do następnego atrybutu. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| **bool** [Read](./read/)() override | Odczytuje kolejny węzeł ze strumienia. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parsuje wartość atrybutu do jednego lub więcej węzłów **[Text](../../system.text/)**, **EntityReference** lub **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekoduje Base64 i zwraca zdekodowane bajty binarne. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekoduje **BinHex** i zwraca zdekodowane bajty binarne. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Odczytuje zawartość tekstową elementu do bufora znaków. Ta metoda jest przeznaczona do odczytywania dużych strumieni osadzonego tekstu poprzez kolejno wywoływanie jej. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość jako obiekt określonego typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca binarne bajty odkodowane z **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca binarne bajty odkodowane z **BinHex**. |
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
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość elementu jako żądany typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje jego zawartość jako żądany typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Odczytuje bieżący element i zwraca jego zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Odczytuje bieżący element i zwraca jego zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Odczytuje bieżący element i zwraca jego zawartość jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana nazwa lokalna i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje go i zwraca jego zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Odczytuje element zawierający wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ oferuje ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Sprawdza, czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu pasuje do podanego ciągu przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ oferuje ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy wartości [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) znalezionego elementu pasują do podanych ciągów przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ oferuje ona prostszy sposób obsługi tej operacji. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Sprawdza, czy bieżący węzeł treści jest znacznikiem zamknięcia i przesuwa czytnik do następnego węzła. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Po nadpisaniu w klasie pochodnej odczytuje całą zawartość, włącznie z znacznikami, jako ciąg znaków. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Po nadpisaniu w klasie pochodnej odczytuje zawartość, włącznie ze znacznikami, reprezentującą ten węzeł oraz wszystkie jego elementy potomne. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Sprawdza, czy bieżący węzeł treści jest elementem o podanej wartości [XmlReader::get_Name](../xmlreader/get_name/) i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy bieżący węzeł treści jest elementem o podanych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) i przesuwa czytnik do następnego węzła. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Odczytuje zawartość elementu lub węzła tekstowego jako ciąg znaków. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Zwraca nową instancję [XmlReader](../xmlreader/), którą można użyć do odczytania bieżącego węzła oraz wszystkich jego potomków. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o określonej nazwie kwalifikowanej. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o określonej nazwie lokalnej i URI przestrzeni nazw. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Czyta, aż zostanie znaleziony element o określonej nazwie kwalifikowanej. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Czyta, aż zostanie znaleziony element o określonej nazwie lokalnej i URI przestrzeni nazw. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o określonej nazwie kwalifikowanej. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o określonej nazwie lokalnej i URI przestrzeni nazw. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Odczytuje duże strumienie tekstu osadzone w dokumencie XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartość z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych odwołań o podaną wartość. |
| void [ResetState](./resetstate/)() | Resetuje stan czytnika do [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Rozwiązuje odwołanie encji dla węzłów **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Ustawia wyliczenie DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Ustawia wartość określającą, w jaki sposób czytnik obsługuje encje. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ustawia wartość wskazującą, czy włączyć obsługę przestrzeni nazw. |
| void [set_Normalization](./set_normalization/)(**bool**) | Ustawia wartość wskazującą, czy normalizować białe znaki i wartości atrybutów. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Ustawia wartość wskazującą, czy zezwolić na przetwarzanie DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Ustawia wartość określającą, jak obsługiwać białe znaki. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ustawia [XmlResolver](../xmlresolver/) używany do rozwiązywania odwołań DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych odwołań. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Skip](./skip/)() override | Pomija dzieci bieżącego węzła. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych odwołań. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję klasy [XmlTextReader](./) z określonym strumieniem. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję klasy [XmlTextReader](./) z określonym URL i strumieniem. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Tworzy nową instancję klasy [XmlTextReader](./) z określonym strumieniem i [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Tworzy nową instancję klasy [XmlTextReader](./) z określonym URL, strumieniem i [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego TextReadera. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego URL i TextReadera. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego TextReadera oraz [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego URL, TextReadera i [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego strumienia, XmlNodeType oraz [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego string, XmlNodeType oraz [XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego pliku. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicjalizuje nową instancję klasy [XmlTextReader](./) przy użyciu określonego pliku oraz [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Typedefy

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias do współdzielonego wskaźnika na instancję tej klasy. |
## Uwagi

Zaleca się użycie klasy [XmlReader](../xmlreader/) zamiast tego. 

Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika, aby przekazać ją do funkcji jako argument. 

## Zobacz także

* Klasa [XmlReader](../xmlreader/)
* Klasa [IXmlLineInfo](../ixmllineinfo/)
* Klasa [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)