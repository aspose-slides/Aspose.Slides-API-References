---
title: XmlNode
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje pojedynczy węzeł w dokumencie XML.
type: docs
weight: 326
url: /pl/system.xml/xmlnode/
---
## XmlNode klasa


Represents a single node in the XML document.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Metody

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Dodaje określony węzeł na koniec listy węzłów potomnych tego węzła. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Zwraca iterator wskazujący na pierwszy element (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany referencjonowanego obiektu, ponieważ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Zwraca iterator wskazujący na pierwszy element (jeśli istnieje) const-kwalifikowanej instancji kolekcji. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Zwraca iterator wskazujący na pierwszy const-kwalifikowany element (jeśli istnieje) kolekcji. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Zwraca iterator wskazujący tuż po ostatnim const-kwalifikowanym elemencie (jeśli istnieje) kolekcji. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [Clone](./clone/)() | Tworzy duplikat tego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [CloneNode](./clonenode/)(**bool**) | Tworzy duplikat węzła, gdy zostanie przesłonięte w klasie pochodnej. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | Tworzy XPathNavigator do nawigacji po tym obiekcie. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Zwraca iterator wskazujący tuż po ostatnim elemencie (jeśli istnieje) kolekcji. Ten iterator nie może być używany do zmiany referencjonowanego obiektu, ponieważ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) zwraca kopię obiektu typu T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Zwraca iterator wskazujący tuż po ostatnim elemencie (jeśli istnieje) const-kwalifikowanej instancji kolekcji. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](./get_attributes/)() | Zwraca [XmlAttributeCollection](../xmlattributecollection/) zawierający atrybuty tego węzła. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Zwraca bazowy URI bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](./get_childnodes/)() | Zwraca wszystkie węzły potomne tego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_FirstChild](./get_firstchild/)() | Zwraca pierwszego potomka tego węzła. |
| virtual **bool** [get_HasChildNodes](./get_haschildnodes/)() | Zwraca wartość wskazującą, czy ten węzeł ma jakiekolwiek węzły potomne. |
| virtual [String](../../system/string/) [get_InnerText](./get_innertext/)() | Zwraca połączone wartości węzła i wszystkich jego węzłów potomnych. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Zwraca znacznik reprezentujący wyłącznie węzły potomne tego węzła. |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() | Zwraca wartość wskazującą, czy węzeł jest tylko do odczytu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_LastChild](./get_lastchild/)() | Zwraca ostatniego potomka tego węzła. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Zwraca lokalną nazwę węzła, gdy zostanie przesłonięte w klasie pochodnej. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Zwraca w pełni kwalifikowaną nazwę węzła, gdy zostanie przesłonięte w klasie pochodnej. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Zwraca URI przestrzeni nazw tego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_NextSibling](./get_nextsibling/)() | Zwraca węzeł bezpośrednio następujący po tym węźle. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Zwraca typ bieżącego węzła, gdy zostanie przesłonięte w klasie pochodnej. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Zwraca znacznik zawierający ten węzeł i wszystkie jego węzły potomne. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() | Zwraca [XmlDocument](../xmldocument/), do którego należy ten węzeł. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_ParentNode](./get_parentnode/)() | Zwraca rodzica tego węzła (dla węzłów, które mogą mieć rodziców). |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Zwraca prefiks przestrzeni nazw tego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousSibling](./get_previoussibling/)() | Zwraca węzeł bezpośrednio poprzedzający ten węzeł. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousText](./get_previoustext/)() | Zwraca węzeł tekstowy, który bezpośrednio poprzedza ten węzeł. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Zwraca infoset po walidacji schematu, który został przypisany do tego węzła w wyniku walidacji schematu. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Zwraca wartość węzła. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>\>\> [GetEnumerator](./getenumerator/)() override | Zwraca enumerator iterujący po węzłach potomnych w bieżącym węźle. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](./getnamespaceofprefix/)([String](../../system/string/)) | Wyszukuje najbliższą deklarację **xmlns** dla podanego prefiksu znajdującą się w zasięgu bieżącego węzła i zwraca URI przestrzeni nazw w deklaracji. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](./getprefixofnamespace/)([String](../../system/string/)) | Wyszukuje najbliższą deklarację **xmlns** dla podanego URI przestrzeni nazw znajdującą się w zasięgu bieżącego węzła i zwraca prefiks zdefiniowany w tej deklaracji. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analogiczny wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/)) | Zwraca pierwszy element potomny o określonym [XmlNode::get_Name](./get_name/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Zwraca pierwszy element potomny o określonych wartościach [XmlNode::get_LocalName](./get_localname/) i [XmlNode::get_NamespaceURI](./get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Wstawia określony węzeł bezpośrednio po wskazanym węźle referencyjnym. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Wstawia określony węzeł bezpośrednio przed wskazanym węzłem referencyjnym. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Stosuje funkcję akumulatora na sekwencji. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Określa, czy wszystkie elementy sekwencji spełniają warunek. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Określa, czy sekwencja zawiera jakiekolwiek elementy. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Określa, czy istnieje jakikolwiek element sekwencji lub spełnia warunek. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Oblicza średnią z sekwencji wartości numerycznych. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Oblicza średnią z sekwencji wartości uzyskanych przez wywołanie funkcji transformującej na każdym elemencie sekwencji wejściowej. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Rzutuje elementy na określony typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Łączy dwie sekwencje. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Określa, czy sekwencja zawiera określoną wartość. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Zwraca liczbę elementów w sekwencji (obliczoną poprzez bezpośrednie liczenie). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca liczbę elementów w sekwencji, które spełniają określony warunek. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Zwraca element o podanym indeksie w sekwencji. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Zwraca pierwszy element sekwencji. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Zwraca pierwszy element sekwencji, który spełnia określony warunek. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Zwraca pierwszy element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Zwraca pierwszy element sekwencji spełniający warunek lub wartość domyślną, jeśli takiego elementu nie znaleziono. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Grupuje elementy sekwencji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Grupuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Zwraca ostatni element sekwencji. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Zwraca ostatni element sekwencji lub wartość domyślną, jeśli sekwencja jest pusta. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie generycznej sekwencji i zwraca maksymalną otrzymaną wartość. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Wywołuje funkcję transformującą na każdym elemencie generycznej sekwencji i zwraca minimalną otrzymaną wartość. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtruje elementy sekwencji na podstawie określonego typu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w porządku rosnącym według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortuje elementy sekwencji w porządku malejącym według wartości kluczy wybranych przez keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Odwraca kolejność elementów w sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformuje elementy sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformuje każdy element sekwencji do nowej postaci, uwzględniając indeks elementu. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektuje każdy element sekwencji i łączy powstałe sekwencje w jedną sekwencję. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Pomija określoną liczbę kolejnych elementów od początku sekwencji i zwraca resztę. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Zwraca określoną liczbę kolejnych elementów od początku sekwencji. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Tworzy tablicę z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Tworzy List<T> z sekwencji. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtruje sekwencję na podstawie określonego predykatu. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| virtual void [Normalize](./normalize/)() | Umieszcza wszystkie węzły [XmlText](../xmltext/) w pełnej głębokości poddrzewa pod tym [XmlNode](./) w „normalną” formę, gdzie jedynie znaczniki (tagi, komentarze, instrukcje przetwarzania, sekcje CDATA i odwołania do encji) oddzielają węzły [XmlText](../xmltext/), czyli nie ma sąsiadujących węzłów [XmlText](../xmltext/). |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Dodaje określony węzeł na początek listy węzłów potomnych tego węzła. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| virtual void [RemoveAll](./removeall/)() | Usuwa wszystkie węzły potomne i/lub atrybuty bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [RemoveChild](./removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Usuwa określony węzeł potomny. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [ReplaceChild](./replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Zastępuje węzeł potomny **oldChild** węzłem **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&) | Wybiera listę węzłów pasujących do wyrażenia [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wybiera listę węzłów pasujących do wyrażenia [XPath](../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../system.xml.xpath/) są rozwiązywane przy użyciu dostarczonego [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&) | Wybiera pierwszy [XmlNode](./) pasujący do wyrażenia [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Wybiera pierwszy [XmlNode](./) pasujący do wyrażenia [XPath](../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../system.xml.xpath/) są rozwiązywane przy użyciu dostarczonego [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual void [set_InnerText](./set_innertext/)([String](../../system/string/)) | Ustawia połączone wartości węzła i wszystkich jego węzłów potomnych. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Ustawia znacznik reprezentujący wyłącznie węzły potomne tego węzła. |
| virtual void [set_Prefix](./set_prefix/)([String](../../system/string/)) | Ustawia prefiks przestrzeni nazw tego węzła. |
| virtual void [set_Value](./set_value/)([String](../../system/string/)) | Ustawia wartość węzła. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual **bool** [Supports](./supports/)([String](../../system/string/), [String](../../system/string/)) | Testuje, czy implementacja DOM obsługuje określoną funkcję. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Zwraca implementację stałego iteratora begin dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Zwraca implementację iteratora begin dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Zwraca implementację stałego iteratora end dla bieżącego kontenera. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Zwraca implementację iteratora end dla bieżącego kontenera. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Zapisuje wszystkie węzły potomne węzła do określonego [XmlWriter](../xmlwriter/), gdy zostanie przesłonięte w klasie pochodnej. |
| virtual void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Zapisuje bieżący węzeł do określonego [XmlWriter](../xmlwriter/), gdy zostanie przesłonięte w klasie pochodnej. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typowa | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Zobacz także

* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Klasa [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)