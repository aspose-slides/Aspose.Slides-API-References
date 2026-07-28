---
title: XmlDocument
second_title: Referencja API Aspose.Slides for C++
description: Reprezentuje dokument XML. Możesz używać tej klasy do wczytywania, walidacji, edycji, dodawania i pozycjonowania XML w dokumencie.
type: docs
weight: 183
url: /pl/system.xml/xmldocument/
---
## XmlDocument klasa

Represents an XML document. You can use this class to load, validate, edit, add, and position XML in a document.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Dodaje określony węzeł na koniec listy węzłów potomnych tego węzła. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Uzyskuje iterator wskazujący na pierwszy element (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany odwoływanego obiektu, ponieważ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) zwraca obiekt-kopię typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Uzyskuje iterator wskazujący na pierwszy element (jeśli istnieje) stałej wersji kolekcji. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Uzyskuje iterator wskazujący na pierwszy element oznaczony jako const (jeśli istnieje) w kolekcji. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Uzyskuje iterator wskazujący bezpośrednio po ostatnim elemencie oznaczonym jako const (jeśli istnieje) w kolekcji. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Tworzy duplikat tego węzła. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Tworzy duplikat tego węzła. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&) | Tworzy [XmlAttribute](../xmlattribute/) o podanej nazwie. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlAttribute](../xmlattribute/) o podanej nazwie kwalifikowanej i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlAttribute](../xmlattribute/) o podanych [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlCDataSection](../xmlcdatasection/)\> [CreateCDataSection](./createcdatasection/)(const [String](../../system/string/)\&) | Tworzy [XmlCDataSection](../xmlcdatasection/) zawierający podane dane. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlComment](../xmlcomment/)\> [CreateComment](./createcomment/)(const [String](../../system/string/)\&) | Tworzy [XmlComment](../xmlcomment/) zawierający podane dane. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentFragment](../xmldocumentfragment/)\> [CreateDocumentFragment](./createdocumentfragment/)() | Tworzy [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [CreateDocumentType](./createdocumenttype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zwraca nowy obiekt [XmlDocumentType](../xmldocumenttype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&) | Tworzy element o podanej nazwie. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlElement](../xmlelement/) o kwalifikowanej nazwie i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy element o podanych [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlEntityReference](../xmlentityreference/)\> [CreateEntityReference](./createentityreference/)(const [String](../../system/string/)\&) | Tworzy [XmlEntityReference](../xmlentityreference/) o podanej nazwie. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | Tworzy nowy obiekt XPathNavigator do nawigacji w tym dokumencie. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlNode](../xmlnode/) o podanym XmlNodeType, [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_Name](./get_name/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlNode](../xmlnode/) o podanym typie węzła, [XmlDocument::get_Name](./get_name/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlNode](../xmlnode/) o podanym XmlNodeType, [XmlDocument::get_Name](./get_name/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlProcessingInstruction](../xmlprocessinginstruction/)\> [CreateProcessingInstruction](./createprocessinginstruction/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy [XmlProcessingInstruction](../xmlprocessinginstruction/) o podanej nazwie i danych. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlSignificantWhitespace](../xmlsignificantwhitespace/)\> [CreateSignificantWhitespace](./createsignificantwhitespace/)(const [String](../../system/string/)\&) | Tworzy węzeł [XmlSignificantWhitespace](../xmlsignificantwhitespace/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](../xmltext/)\> [CreateTextNode](./createtextnode/)(const [String](../../system/string/)\&) | Tworzy [XmlText](../xmltext/) o podanym tekście. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWhitespace](../xmlwhitespace/)\> [CreateWhitespace](./createwhitespace/)(const [String](../../system/string/)\&) | Tworzy węzeł [XmlWhitespace](../xmlwhitespace/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDeclaration](../xmldeclaration/)\> [CreateXmlDeclaration](./createxmldeclaration/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Tworzy węzeł [XmlDeclaration](../xmldeclaration/) o podanych wartościach. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Uzyskuje iterator wskazujący bezpośrednio po ostatnim elemencie (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany odwoływanego obiektu, ponieważ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) zwraca obiekt-kopię typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Uzyskuje iterator wskazujący bezpośrednio po ostatnim elemencie (jeśli istnieje) stałej wersji kolekcji. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Zwraca [XmlAttributeCollection](../xmlattributecollection/) zawierający atrybuty tego węzła. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Zwraca podstawowy URI bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Zwraca wszystkie węzły potomne tego węzła. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [get_DocumentElement](./get_documentelement/)() | Zwraca korzeń [XmlElement](../xmlelement/) dokumentu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [get_DocumentType](./get_documenttype/)() | Zwraca węzeł zawierający deklarację DOCTYPE. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Zwraca pierwszego potomka węzła. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Zwraca wartość wskazującą, czy węzeł ma jakiekolwiek węzły potomne. |
| [SharedPtr](../../system/sharedptr/)\<[XmlImplementation](../xmlimplementation/)\> [get_Implementation](./get_implementation/)() | Zwraca obiekt [XmlImplementation](../xmlimplementation/) bieżącego dokumentu. |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | Zwraca połączone wartości węzła i wszystkich jego węzłów potomnych. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Zwraca znacznik reprezentujący potomków bieżącego węzła. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | Zwraca wartość wskazującą, czy bieżący węzeł jest tylko do odczytu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Zwraca ostatniego potomka węzła. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Zwraca lokalną nazwę węzła. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca kwalifikowaną nazwę węzła. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Zwraca URI przestrzeni nazw tego węzła. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Zwraca [XmlNameTable](../xmlnametable/) powiązany z tą implementacją. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Zwraca węzeł następujący bezpośrednio po tym węźle. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Zwraca typ bieżącego węzła. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Zwraca znacznik zawierający ten węzeł i wszystkie jego węzły potomne. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](./)\> [get_OwnerDocument](./get_ownerdocument/)() override | Zwraca [XmlDocument](./) do którego należy bieżący węzeł. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Zwraca rodzica tego węzła (dla węzłów, które mogą mieć rodziców). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Zwraca prefiks przestrzeni nazw tego węzła. |
| **bool** [get_PreserveWhitespace](./get_preservewhitespace/)() | Zwraca wartość wskazującą, czy zachować białe znaki w treści elementu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Zwraca węzeł bezpośrednio poprzedzający ten węzeł. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Zwraca węzeł tekstowy, który bezpośrednio poprzedza ten węzeł. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Zwraca Post-Schema-Validation-Infoset (PSVI) węzła. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Zwraca obiekt XmlSchemaSet powiązany z tym [XmlDocument](./). |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Zwraca wartość węzła. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Uzyskuje strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [GetElementById](./getelementbyid/)([String](../../system/string/)) | Zwraca [XmlElement](../xmlelement/) o podanym ID. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | Zwraca [XmlNodeList](../xmlnodelist/) zawierający listę wszystkich elementów potomnych pasujących do podanej nazwy. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | Zwraca [XmlNodeList](../xmlnodelist/) zawierający listę wszystkich elementów potomnych pasujących do podanych [XmlDocument::get_LocalName](./get_localname/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Zwraca enumerator iterujący przez węzły potomne w bieżącym węźle. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Wyszukuje najbliższą deklarację **xmlns** dla podanego prefiksu obowiązującą w bieżącym węźle i zwraca URI przestrzeni nazw w tej deklaracji. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Wyszukuje najbliższą deklarację **xmlns** dla podanego URI przestrzeni nazw obowiązującą w bieżącym węźle i zwraca prefiks zdefiniowany w tej deklaracji. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Uzyskuje rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Zwraca pierwszy element potomny o podanym [XmlNode::get_Name](../xmlnode/get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Zwraca pierwszy element potomny o podanych wartościach [XmlNode::get_LocalName](../xmlnode/get_localname/) i [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ImportNode](./importnode/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, **bool**) | Importuje węzeł z innego dokumentu do bieżącego dokumentu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Wstawia podany węzeł bezpośrednio po podanym węźle referencyjnym. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Wstawia podany węzeł bezpośrednio przed podanym węzłem referencyjnym. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Zastosowuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje jakikolwiek element sekwencji lub spełnia warunek. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Oblicza średnią z sekwencji wartości numerycznych. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią z sekwencji wartości uzyskanych przez wywołanie funkcji transformującej na każdym elemencie sekwencji wejściowej. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Rzutuje elementy na podany typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Łączy dwie sekwencje. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczaną poprzez bezpośrednie liczenie). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji spełniających podany warunek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Zwraca pierwszy element sekwencji. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca pierwszy element sekwencji spełniający podany warunek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Zwraca pierwszy element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element sekwencji, który spełnia warunek, lub wartość domyślną, jeśli taki element nie zostanie znaleziony. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupuje elementy sekwencji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Zwraca ostatni element sekwencji. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Zwraca ostatni element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformacji na każdym elemencie ogólnej sekwencji i zwraca maksymalną uzyskaną wartość. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformacji na każdym elemencie ogólnej sekwencji i zwraca minimalną uzyskaną wartość. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje elementy sekwencji na podstawie określonego typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w kolejności rosnącej według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w kolejności malejącej według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element sekwencji do nowej formy, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element sekwencji i łączy powstałe sekwencje w jedną sekwencję. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku sekwencji i zwraca pozostałe. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję na podstawie określonego predykatu. |
| virtual void [Load](./load/)([String](../../system/string/)) | Ładuje dokument XML z podanego URL. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Ładuje dokument XML z określonego strumienia. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | Ładuje dokument XML z podanego TextReader. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | Ładuje dokument XML z podanego [XmlReader](../xmlreader/). |
| virtual void [LoadXml](./loadxml/)([String](../../system/string/)) | Ładuje dokument XML z podanego ciągu znaków. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu obserwatora [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| virtual void [Normalize](../xmlnode/normalize/)() | Umieszcza wszystkie węzły [XmlText](../xmltext/) w pełnej głębokości poddrzewa pod tym [XmlNode](../xmlnode/) w „normalną” formę, w której jedynie znacznik (tj. tagi, komentarze, instrukcje przetwarzania, sekcje CDATA i odwołania do encji) oddziela węzły [XmlText](../xmltext/), czyli nie ma przylegających węzłów [XmlText](../xmltext/). |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Dodaje określony węzeł na początek listy węzłów potomnych tego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReadNode](./readnode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | Tworzy obiekt [XmlNode](../xmlnode/) na podstawie informacji w [XmlReader](../xmlreader/). Czytnik musi być ustawiony na węzeł lub atrybut. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowy z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Usuwa wszystkie węzły potomne i/lub atrybuty bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Usuwa określony węzeł potomny. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Zastępuje węzeł potomny **oldChild** węzłem **newChild**. |
| virtual void [Save](./save/)([String](../../system/string/)) | Zapisuje dokument XML do określonego pliku. Jeśli podany plik istnieje, metoda go nadpisuje. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Zapisuje dokument XML do określonego strumienia. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>) | Zapisuje dokument XML do podanego TextWriter. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>) | Zapisuje dokument XML do podanego [XmlWriter](../xmlwriter/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Wybiera listę węzłów pasujących do wyrażenia [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wybiera listę węzłów pasujących do wyrażenia [XPath](../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../system.xml.xpath/) są rozwiązywane przy użyciu dostarczonego [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Wybiera pierwszy [XmlNode](../xmlnode/), który pasuje do wyrażenia [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wybiera pierwszy [XmlNode](../xmlnode/), który pasuje do wyrażenia [XPath](../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../system.xml.xpath/) są rozwiązywane przy użyciu dostarczonego [XmlNamespaceManager](../xmlnamespacemanager/). |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Rzuca wyjątek InvalidOperationException we wszystkich przypadkach. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Ustawia znacznik reprezentujący dzieci bieżącego węzła. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Ustawia prefiks przestrzeni nazw tego węzła. |
| void [set_PreserveWhitespace](./set_preservewhitespace/)(**bool**) | Ustawia wartość określającą, czy zachować białe znaki w treści elementu. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Ustawia obiekt XmlSchemaSet powiązany z tym [XmlDocument](./). |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Ustawia wartość węzła. |
| virtual void [set_XmlResolver](./set_xmlresolver/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>) | Ustawia [XmlResolver](../xmlresolver/) używany do rozwiązywania zasobów zewnętrznych. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Sprawdza, czy implementacja DOM obsługuje określoną funkcję. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu obserwatora [LockContext](../../system/lockcontext/). |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Weryfikuje [XmlDocument](./) względem schematów XML [Schema](../../system.xml.schema/) Definition Language (XSD) zawartych w liście [XmlDocument::get_Schemas](./get_schemas/). |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Weryfikuje określony obiekt [XmlNode](../xmlnode/) względem schematów XML [Schema](../../system.xml.schema/) Definition Language (XSD) znajdujących się w liście [XmlDocument::get_Schemas](./get_schemas/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Pobiera implementację stałego iteratora begin dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Pobiera implementację iteratora begin dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Pobiera implementację stałego iteratora end dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Pobiera implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Zapisuje wszystkie dzieci węzła [XmlDocument](./) do określonego [XmlWriter](../xmlwriter/). |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Zapisuje węzeł [XmlDocument](./) do określonego [XmlWriter](../xmlwriter/). |
|  [XmlDocument](./xmldocument/)() | Inicjalizuje nową instancję klasy [XmlDocument](./). |
|  [XmlDocument](./xmldocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Inicjalizuje nową instancję klasy [XmlDocument](./) z określonym [XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |

## Uwagi

Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu. 

## Zobacz także

* Klasa [XmlNode](../xmlnode/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)