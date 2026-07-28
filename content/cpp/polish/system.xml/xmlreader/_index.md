---
title: XmlReader
second_title: Aspose.Slides dla C++ - referencja API
description: Reprezentuje czytnik, który zapewnia szybki, niebuforowany, jedynie sekwencyjny dostęp do danych XML.
type: docs
weight: 430
url: /pl/system.xml/xmlreader/
---
## XmlReader klasa

Reprezentuje czytnik zapewniający szybki, niebuforowany, jednokierunkowy dostęp do danych XML.

```cpp
class XmlReader : public System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [Close](./close/)() | Gdy zostanie przesłonięta w klasie pochodnej, zmienia [XmlReader::get_ReadState](./get_readstate/) na [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](./) z określonym URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego URI, ustawień i informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego strumienia z domyślnymi ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](./) z określonym strumieniem i ustawieniami. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego strumienia, bazowego URI i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego strumienia, ustawień i informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego czytnika tekstu. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego czytnika tekstu i ustawień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego czytnika tekstu, ustawień i bazowego URI. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego czytnika tekstu, ustawień i informacji kontekstowych do parsowania. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Tworzy nową instancję [XmlReader](./) przy użyciu określonego czytnika XML i ustawień. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca liczbę atrybutów bieżącego węzła. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca bazowy URI bieżącego węzła. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | Zwraca wartość wskazującą, czy [XmlReader](./) implementuje metody odczytu binarnego zawartości. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | Zwraca wartość wskazującą, czy [XmlReader](./) implementuje metodę [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Zwraca wartość wskazującą, czy ten czytnik może analizować i rozwiązywać encje. |
| virtual **int32_t** [get_Depth](./get_depth/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca głębokość bieżącego węzła w dokumencie XML. |
| virtual **bool** [get_EOF](./get_eof/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość wskazującą, czy czytnik znajduje się na końcu strumienia. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Zwraca wartość wskazującą, czy bieżący węzeł posiada jakiekolwiek atrybuty. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość wskazującą, czy bieżący węzeł może mieć wartość [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość wskazującą, czy bieżący węzeł jest atrybutem wygenerowanym z domyślnej wartości zdefiniowanej w DTD lub schemacie. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość wskazującą, czy bieżący węzeł jest pustym elementem (na przykład **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca lokalną nazwę bieżącego węzła. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca kwalifikowaną nazwę bieżącego węzła. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca URI przestrzeni nazw (zgodnie z definicją W3C Namespace) węzła, na którym znajduje się czytnik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca [XmlNameTable](../xmlnametable/) powiązany z tą implementacją. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca typ bieżącego węzła. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca prefiks przestrzeni nazw powiązany z bieżącym węzłem. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca znak cudzysłowu używany do otaczania wartości węzła atrybutu. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca stan czytnika. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Zwraca informacje schematu przydzielone bieżącemu węzłowi w wyniku walidacji schematu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Zwraca obiekt [XmlReaderSettings](../xmlreadersettings/) użyty do utworzenia tej instancji [XmlReader](./). |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość tekstową bieżącego węzła. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Zwraca typ bieżącego węzła. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca bieżący zakres **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Gdy zostanie przesłonięta w klasie pochodnej, zwraca bieżący zakres **xml:space**. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonej wartości [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonym indeksie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonym indeksie. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonej wartości [XmlReader::get_Name](./get_name/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy podany ciąg znaków jest prawidłową nazwą XML. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Zwraca wartość wskazującą, czy podany ciąg znaków jest prawidłowym tokenem nazwy XML. |
| virtual **bool** [IsStartElement](./isstartelement/)() | Wywołuje [XmlReader::MoveToContent](./movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](./movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu oraz czy wartość [XmlReader::get_Name](./get_name/) znalezionego elementu odpowiada podanemu argumentowi. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | Wywołuje [XmlReader::MoveToContent](./movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu oraz czy wartości [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/) znalezionego elementu odpowiadają podanym ciągom. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | Gdy zostanie przesłonięta w klasie pochodnej, rozwiązuje prefiks przestrzeni nazw w zakresie bieżącego elementu. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonej wartości [XmlReader::get_Name](./get_name/). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonych wartościach [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/). |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do atrybutu o określonym indeksie. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Sprawdza, czy bieżący węzeł jest węzłem zawartości (tekst niebędący białym znakiem, **CDATA**, **Element**, **EndElement**, **EntityReference** lub **EndEntity**). Jeśli węzeł nie jest węzłem zawartości, czytnik pomija go i przechodzi do następnego węzła zawartości lub końca pliku. Pomija węzły następujących typów: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** lub **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do elementu zawierającego bieżący węzeł atrybutu. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do pierwszego atrybutu. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Gdy zostanie przesłonięta w klasie pochodnej, przechodzi do następnego atrybutu. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| virtual **bool** [Read](./read/)() | Gdy zostanie przesłonięta w klasie pochodnej, odczytuje następny węzeł ze strumienia. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | Gdy zostanie przesłonięta w klasie pochodnej, parsuje wartość atrybutu do jednego lub więcej węzłów **[Text](../../system.text/)**, **EntityReference** lub **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość jako obiekt określonego typu. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Odczytuje zawartość i zwraca bajty binarne zdekodowane z Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Odczytuje zawartość i zwraca bajty binarne zdekodowane z **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako [Boolean](../../system/boolean/). |

| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Odczytuje zawartość tekstową w bieżącej pozycji jako obiekt [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Odczytuje zawartość elementu jako żądany typ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje zawartość elementu jako żądany typ. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Odczytuje element i dekoduje zawartość **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Odczytuje element i dekoduje zawartość **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową podwójnej precyzji. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Odczytuje bieżący element i zwraca zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako 32-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Odczytuje bieżący element i zwraca zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako 64-bitową liczbę całkowitą ze znakiem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Odczytuje bieżący element i zwraca zawartość jako [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Odczytuje bieżący element i zwraca zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy podana lokalna nazwa i URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako obiekt [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Odczytuje element zawierający wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Sprawdza, czy wartość [XmlReader::get_Name](./get_name/) znalezionego elementu odpowiada podanemu łańcuchowi przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy wartości [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/) znalezionego elementu odpowiadają podanym łańcuchom przed odczytaniem elementu zawierającego wyłącznie tekst. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual void [ReadEndElement](./readendelement/)() | Sprawdza, czy bieżący węzeł zawartości jest tagiem zamykającym i przesuwa czytnik do następnego węzła. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | Po nadpisaniu w klasie pochodnej odczytuje całą zawartość, w tym znacznikowanie, jako łańcuch znaków. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | Po nadpisaniu w klasie pochodnej odczytuje zawartość, w tym znacznikowanie, reprezentującą ten węzeł i wszystkie jego potomki. |
| virtual void [ReadStartElement](./readstartelement/)() | Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanej wartości [XmlReader::get_Name](./get_name/) i przesuwa czytnik do następnego węzła. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy bieżący węzeł zawartości jest elementem o podanych wartościach [XmlReader::get_LocalName](./get_localname/) i [XmlReader::get_NamespaceURI](./get_namespaceuri/) i przesuwa czytnik do następnego węzła. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Po nadpisaniu w klasie pochodnej odczytuje zawartość elementu lub węzła tekstowego jako łańcuch znaków. Zaleca się jednak użycie metody [XmlReader::ReadElementContentAsString](./readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Zwraca nową instancję [XmlReader](./), którą można użyć do odczytu bieżącego węzła i wszystkich jego potomków. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Przesuwa [XmlReader](./) do następnego elementu potomnego o określonej kwalifikowanej nazwie. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](./) do następnego elementu potomnego o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Czyta aż zostanie znaleziony element o określonej kwalifikowanej nazwie. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Czyta aż zostanie znaleziony element o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Przesuwa [XmlReader](./) do następnego elementu siostrzanego o określonej kwalifikowanej nazwie. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Przesuwa [XmlReader](./) do następnego elementu siostrzanego o określonej lokalnej nazwie i URI przestrzeni nazw. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Odczytuje duże strumienie tekstu osadzone w dokumencie XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [ResolveEntity](./resolveentity/)() | Po nadpisaniu w klasie pochodnej rozwiązuje odwołanie encji dla węzłów **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [Skip](./skip/)() | Pomija dzieci bieżącego węzła. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)