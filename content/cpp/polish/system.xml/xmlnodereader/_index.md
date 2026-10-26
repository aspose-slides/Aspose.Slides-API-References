---
title: XmlNodeReader
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje czytnik, który zapewnia szybki, niebuforowany dostęp jedynie w przód do danych XML w obiekcie XmlNode.
type: docs
weight: 365
url: /pl/system.xml/xmlnodereader/
---
## XmlNodeReader klasa

Reprezentuje czytnik, który zapewnia szybki, niebuforowany dostęp tylko w przód do danych XML w [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metody

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Zmienia [XmlNodeReader::get_ReadState](./get_readstate/) na [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego URI, ustawień oraz informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia z domyślnymi ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) z określonym strumieniem i ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, podstawowego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego strumienia, ustawień oraz informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień oraz podstawowego URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika tekstu, ustawień i informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Tworzy nową instancję [XmlReader](../xmlreader/) przy użyciu określonego czytnika XML i ustawień. |
| void [Dispose](../xmlreader/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwie wartości NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równa żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwie wartości NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równa żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Zwraca liczbę atrybutów bieżącego węzła. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Zwraca podstawowy URI bieżącego węzła. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | Zwraca wartość wskazującą, czy [XmlNodeReader](./) implementuje metody odczytu zawartości binarnej. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | Zwraca wartość wskazującą, czy [XmlReader](../xmlreader/) implementuje metodę [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Zwraca wartość wskazującą, czy ten czytnik może analizować i rozwiązywać jednostki. |
| **int32_t** [get_Depth](./get_depth/)() override | Zwraca głębokość bieżącego węzła w dokumencie XML. |
| **bool** [get_EOF](./get_eof/)() override | Zwraca wartość wskazującą, czy czytnik jest ustawiony na końcu strumienia. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Zwraca wartość wskazującą, czy bieżący węzeł ma jakiekolwiek atrybuty. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Zwraca wartość wskazującą, czy bieżący węzeł może mieć wartość [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest atrybutem wygenerowanym z wartości domyślnej określonej w definicji typu dokumentu (DTD) lub schemacie. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest pustym elementem (na przykład **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Zwraca lokalną nazwę bieżącego węzła. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca pełną (zakwalifikowaną) nazwę bieżącego węzła. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Zwraca URI przestrzeni nazw (zgodnie z definicją W3C Namespace) węzła, na którym znajduje się czytnik. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Zwraca [XmlNameTable](../xmlnametable/) powiązany z tą implementacją. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Zwraca typ bieżącego węzła. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Zwraca prefiks przestrzeni nazw powiązany z bieżącym węzłem. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Gdy zostanie przesłonięta w klasie pochodnej, pobiera znak cudzysłowu używany do otaczania wartości węzła atrybutu. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Zwraca stan czytnika. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Zwraca informacje o schemacie przypisane do bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Zwraca obiekt [XmlReaderSettings](../xmlreadersettings/) użyty do utworzenia tej instancji [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | Zwraca wartość tekstową bieżącego węzła. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Zwraca typ bieżącego węzła. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Zwraca bieżący **xml:lang** zakres. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Zwraca bieżący **xml:space** zakres. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Zwraca wartość atrybutu o podanej nazwie. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Zwraca wartość atrybutu o podanej nazwie lokalnej i URI przestrzeni nazw. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Zwraca wartość atrybutu o podanym indeksie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Gdy zostanie przesłonięta w klasie pochodnej, pobiera wartość atrybutu o podanym indeksie. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, pobiera wartość atrybutu o podanej wartości [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, pobiera wartość atrybutu o podanych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłową nazwą XML. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy argument typu string jest prawidłowym tokenem nazwy XML. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest znacznikem początkowym lub pustym elementem. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest znacznikem początkowym lub pustym elementem oraz czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu pasuje do podanego argumentu. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](../xmlreader/movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest znacznikem początkowym lub pustym elementem oraz czy wartości [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) znalezionego elementu pasują do podanych ciągów. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Przechodzi do atrybutu o podanej nazwie. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Przechodzi do atrybutu o podanej nazwie lokalnej i URI przestrzeni nazw. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Przechodzi do atrybutu o podanym indeksie. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Sprawdza, czy bieżący węzeł jest węzłem zawartości (tekst niebędący białymi znakami, **CDATA**, **Element**, **EndElement**, **EntityReference** lub **EndEntity**). Jeśli węzeł nie jest węzłem zawartości, czytnik przeskakuje do następnego węzła zawartości lub końca pliku. Pomija węzły następujących typów: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** lub **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Przechodzi do elementu zawierającego bieżący węzeł atrybutu. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | Przechodzi do pierwszego atrybutu. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Przechodzi do następnego atrybutu. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Tak naprawdę nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów w klasach pochodnych. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Tak naprawdę nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów w klasach pochodnych. |
| **bool** [Read](./read/)() override | Odczytuje kolejny węzeł ze strumienia. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Parsuje wartość atrybutu na jeden lub więcej węzłów **[Text](../../system.text/)**, **EntityReference** lub **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość jako obiekt określonego typu. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca bajty binarne po dekodowaniu Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje zawartość i zwraca bajty binarne po dekodowaniu BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Odczytuje treść tekstową w bieżącej pozycji jako [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Odczytuje treść tekstową w bieżącej pozycji jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Odczytuje treść tekstową w bieżącej pozycji jako obiekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Odczytuje treść tekstową w bieżącej pozycji jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Odczytuje treść tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Odczytuje treść tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Odczytuje treść tekstową w bieżącej pozycji jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Odczytuje treść tekstową w bieżącej pozycji jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Odczytuje treść tekstową w bieżącej pozycji jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość elementu jako żądany typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje zawartość elementu jako żądany typ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Odczytuje element i dekoduje zawartość BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Odczytuje bieżący element i zwraca jego zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Odczytuje bieżący element i zwraca jego zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Odczytuje bieżący element i zwraca jego zawartość jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Odczytuje bieżący element i zwraca jego zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca jego zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Odczytuje element zawierający tylko tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Sprawdza, czy wartość [XmlReader::get_Name](../xmlreader/get_name/) znalezionego elementu pasuje do podanego ciągu znaków przed odczytaniem elementu zawierającego tylko tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy wartości [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) znalezionego elementu pasują do podanych ciągów znaków przed odczytaniem elementu zawierającego tylko tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Sprawdza, czy bieżący węzeł zawartości jest tagiem zamykającym i przesuwa czytnik do następnego węzła. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Po nadpisaniu w klasie pochodnej odczytuje całą zawartość, łącznie ze znacznikami, jako ciąg znaków. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Po nadpisaniu w klasie pochodnej odczytuje zawartość, łącznie ze znacznikami, reprezentującą ten węzeł i wszystkie jego elementy potomne. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanej wartości [XmlReader::get_Name](../xmlreader/get_name/) i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanych wartościach [XmlReader::get_LocalName](../xmlreader/get_localname/) i [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) i przesuwa czytnik do następnego węzła. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Odczytuje zawartość elementu lub węzła tekstowego jako ciąg znaków. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Zwraca nową instancję [XmlReader](../xmlreader/), którą można użyć do odczytania bieżącego węzła i wszystkich jego potomków. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o określonej pełnej nazwie. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu potomnego o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Czyta aż zostanie znaleziony element o określonej pełnej nazwie. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Czyta aż zostanie znaleziony element o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o określonej pełnej nazwie. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](../xmlreader/) do następnego elementu rodzeństwa o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Odczytuje duże strumienie tekstu osadzone w dokumencie XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [ResolveEntity](./resolveentity/)() override | Rozwiązuje odwołanie encji dla węzłów **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Skip](./skip/)() override | Pomija dzieci bieżącego węzła. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Tworzy instancję klasy [XmlNodeReader](./) przy użyciu określonego [XmlNode](../xmlnode/). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Uwagi

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## Zobacz także

* Klasa [XmlReader](../xmlreader/)
* Klasa [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)