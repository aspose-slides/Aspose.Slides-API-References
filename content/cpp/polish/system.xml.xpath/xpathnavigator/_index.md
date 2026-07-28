---
title: XPathNavigator
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Udostępnia model kursora do nawigacji i edycji danych XML.
type: docs
weight: 66
url: /pl/system.xml.xpath/xpathnavigator/
---
## XPathNavigator klasa


Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Zwraca obiekt [XmlWriter](../../system.xml/xmlwriter/) używany do tworzenia jednego lub więcej nowych węzłów potomnych na końcu listy węzłów potomnych bieżącego węzła. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła, używając określonego ciągu danych XML. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła, używając zawartości XML obiektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Tworzy nowy węzeł potomny na końcu listy węzłów potomnych bieżącego węzła, używając węzłów w obiekcie [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nowy węzeł elementu potomnego na końcu listy węzłów potomnych bieżącego węzła, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw wraz z podaną wartością. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Weryfikuje, czy dane XML w [XPathNavigator](./) są zgodne ze schematem języka definicji XML [Schema](../../system.xml.schema/) (XSD) podanym. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Po nadpisaniu w klasie pochodnej, tworzy nowy [XPathNavigator](./) umieszczony w tym samym węźle co ten [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Porównuje pozycję bieżącego [XPathNavigator](./) z pozycją określonego [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Kompiluje ciąg reprezentujący wyrażenie [XPath](../) i zwraca obiekt [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy węzeł atrybutu na bieżącym węźle elementu, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw wraz z podaną wartością. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Zwraca obiekt [XmlWriter](../../system.xml/xmlwriter/) używany do tworzenia nowych atrybutów na bieżącym elemencie. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Zwraca kopię [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Usuwa zakres węzłów rodzeństwa od bieżącego węzła do określonego węzła. |
| virtual void [DeleteSelf](./deleteself/)() | Usuwa bieżący węzeł oraz jego węzły potomne. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. Umożliwia haszowanie własnych obiektów. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. Umożliwia haszowanie własnych obiektów. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Oceni określone wyrażenie [XPath](../) i zwraca wynik typowany. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Oceni określone wyrażenie [XPath](../) i zwróci wynik typowany, używając podanego obiektu [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) do rozwiązywania prefiksów przestrzeni nazw w wyrażeniu [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Oceni [XPathExpression](../xpathexpression/) i zwróci wynik typowany. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Używa dostarczonego kontekstu do oceny [XPathExpression](../xpathexpression/) i zwraca wynik typowany. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Po nadpisaniu w klasie pochodnej, pobiera bazowy URI bieżącego węzła. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Zwraca wartość wskazującą, czy [XPathNavigator](./) może edytować podstawowe dane XML. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Zwraca wartość wskazującą, czy bieżący węzeł posiada jakieś atrybuty. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Zwraca wartość wskazującą, czy bieżący węzeł posiada jakiekolwiek węzły potomne. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Zwraca znacznik reprezentujący węzły potomne bieżącego węzła. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Po nadpisaniu w klasie pochodnej, pobiera wartość wskazującą, czy bieżący węzeł jest pustym elementem bez znacznika końcowego. |
| **bool** [get_IsNode](./get_isnode/)() override | Zwraca wartość wskazującą, czy bieżący węzeł reprezentuje węzeł [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Po nadpisaniu w klasie pochodnej, pobiera [XPathNavigator::get_Name](./get_name/) bieżącego węzła bez prefiksu przestrzeni nazw. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Po nadpisaniu w klasie pochodnej, pobiera w pełni kwalifikowaną nazwę bieżącego węzła. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Po nadpisaniu w klasie pochodnej, pobiera URI przestrzeni nazw bieżącego węzła. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Po nadpisaniu w klasie pochodnej, pobiera [XmlNameTable](../../system.xml/xmlnametable/) [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Zwraca [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) używany do porównywania pod kątem równości obiektów [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Po nadpisaniu w klasie pochodnej, pobiera XPathNodeType bieżącego węzła. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Zwraca znacznik reprezentujący otwierające i zamykające tagi bieżącego węzła oraz jego węzłów potomnych. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Po nadpisaniu w klasie pochodnej, pobiera prefiks przestrzeni nazw powiązany z bieżącym węzłem. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Zwraca informacje o schemacie, które zostały przypisane do bieżącego węzła w wyniku walidacji schematu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Zwraca bieżący węzeł jako spakowany obiekt najbardziej odpowiedniego typu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Używany przez [XPathNavigator](./) implementacje, które zapewniają „zwirtualizowany” widok XML nad magazynem, w celu udostępnienia dostępu do obiektów bazowych. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Po nadpisaniu w klasie pochodnej, pobiera wartość **string** elementu. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Zwraca wartość bieżącego węzła jako [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Zwraca wartość bieżącego węzła jako [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Zwraca wartość bieżącego węzła jako [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Zwraca wartość bieżącego węzła jako [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Zwraca wartość bieżącego węzła jako [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Zwraca typ bieżącego węzła. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Zwraca zakres **xml:lang** dla bieżącego węzła. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Zwraca informacje XmlSchemaType dla bieżącego węzła. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Zwraca wartość atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Zwraca wartość węzła przestrzeni nazw odpowiadającego określonej nazwie lokalnej. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Zwraca przestrzenie nazw w zasięgu bieżącego węzła. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołaniu C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Zwraca obiekt [XmlWriter](../../system.xml/xmlwriter/) używany do tworzenia nowego węzła rodzeństwa po aktualnie wybranym węźle. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Tworzy nowy węzeł rodzeństwa po aktualnie wybranym węźle, używając określonego ciągu XML. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Tworzy nowy węzeł rodzenia po aktualnie wybranym węźle, używając zawartości XML obiektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Tworzy nowy węzeł rodzeństwa po aktualnie wybranym węźle, używając węzłów w obiekcie [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Zwraca obiekt [XmlWriter](../../system.xml/xmlwriter/) używany do tworzenia nowego węzła rodzeństwa przed aktualnie wybranym węzłem. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem, używając określonego ciągu XML. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem, używając zawartości XML obiektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Tworzy nowy węzeł rodzeństwa przed aktualnie wybranym węzłem, używając węzłów w obiekcie [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nowy element rodzeństwa po bieżącym węźle, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI wraz z podaną wartością. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nowy element rodzeństwa przed bieżącym węzłem, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI wraz z podaną wartością. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Określa, czy określony [XPathNavigator](./) jest potomkiem bieżącego [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Po nadpisaniu w klasie pochodnej, określa, czy bieżący [XPathNavigator](./) znajduje się w tej samej pozycji co określony [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Zwraca identyfikator URI przestrzeni nazw dla określonego prefiksu. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Zwraca prefiks zadeklarowany dla określonego identyfikatora URI przestrzeni nazw. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Określa, czy bieżący węzeł pasuje do określonego [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Określa, czy bieżący węzeł pasuje do określonego wyrażenia [XPath](../). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Po nadpisaniu w klasie pochodnej, przenosi [XPathNavigator](./) na tę samą pozycję co określony [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Przenosi [XPathNavigator](./) do atrybutu o pasującej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Przenosi [XPathNavigator](./) do węzła potomnego o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Przenosi [XPathNavigator](./) do węzła potomnego określonego typu XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Przenosi [XPathNavigator](./) do pierwszego węzła rodzeństwa bieżącego węzła. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Po nadpisaniu w klasie pochodnej, przenosi [XPathNavigator](./) do pierwszego atrybutu bieżącego węzła. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Po nadpisaniu w klasie pochodnej, przenosi [XPathNavigator](./) do pierwszego węzła potomnego bieżącego węzła. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Po nadpisaniu w klasie pochodnej, przenosi [XPathNavigator](./) do pierwszego węzła przestrzeni nazw, który pasuje do określonego XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Przenosi [XPathNavigator](./) do pierwszego węzła przestrzeni nazw bieżącego węzła. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Przenosi [XPathNavigator](./) do elementu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw w kolejności dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Przenosi [XPathNavigator](./) do elementu o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw, do określonej granicy, w kolejności dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Przenosi [XPathNavigator](./) do następnego elementu typu XPathNodeType określonego w kolejności dokumentu. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Przenosi [XPathNavigator](./) do następnego elementu typu XPathNodeType, do określonej granicy, w kolejności dokumentu. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Po przeładowaniu w klasie pochodnej, przenosi do węzła, który ma atrybut typu **ID**, którego wartość pasuje do określonego [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Przenosi [XPathNavigator](./) do węzła przestrzeni nazw z określonym prefiksem przestrzeni nazw. |
| virtual **bool** [MoveToNext](./movetonext/)() | Po przeładowaniu w klasie pochodnej, przenosi [XPathNavigator](./) do następnego węzła siostrzanego bieżącego węzła. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Przenosi [XPathNavigator](./) do następnego węzła siostrzanego o podanej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Przenosi [XPathNavigator](./) do następnego węzła siostrzanego bieżącego węzła, który pasuje do określonego XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Po przeładowaniu w klasie pochodnej, przenosi [XPathNavigator](./) do następnego atrybutu. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Po przeładowaniu w klasie pochodnej, przenosi [XPathNavigator](./) do kolejnego węzła przestrzeni nazw pasującego do określonego XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Przenosi [XPathNavigator](./) do następnego węzła przestrzeni nazw. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Po przeładowaniu w klasie pochodnej, przenosi [XPathNavigator](./) do węzła nadrzędnego bieżącego węzła. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Po przeładowaniu w klasie pochodnej, przenosi [XPathNavigator](./) do poprzedniego węzła siostrzanego bieżącego węzła. |
| virtual void [MoveToRoot](./movetoroot/)() | Przenosi [XPathNavigator](./) do węzła korzenia, do którego należy bieżący węzeł. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, właściwie, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, właściwie, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Zwraca obiekt [XmlWriter](../../system.xml/xmlwriter/) używany do stworzenia nowego węzła potomnego na początku listy węzłów potomnych bieżącego węzła. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając określonego ciągu XML. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając zawartości XML obiektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Tworzy nowy węzeł potomny na początku listy węzłów potomnych bieżącego węzła, używając węzłów z obiektu [XPathNavigator](./). |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nowy element potomny na początku listy węzłów potomnych bieżącego węzła, używając określonego prefiksu przestrzeni nazw, nazwy lokalnej i identyfikatora URI przestrzeni nazw wraz z podaną wartością. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Zwraca obiekt [XmlReader](../../system.xml/xmlreader/) zawierający bieżący węzeł i jego węzły potomne. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowy z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Zastępuje zakres węzłów siostrzanych od bieżącego węzła do określonego węzła. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Zastępuje bieżący węzeł zawartością określonego ciągu. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Zastępuje bieżący węzeł zawartością określonego obiektu [XmlReader](../../system.xml/xmlreader/). |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Zastępuje bieżący węzeł zawartością określonego obiektu [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Wybiera zestaw węzłów, używając określonego wyrażenia [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wybiera zestaw węzłów przy użyciu określonego wyrażenia [XPath](../) oraz obiektu [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) służącego do rozwiązywania prefiksów przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Wybiera zestaw węzłów przy użyciu określonego [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Wybiera wszystkie węzły przodków bieżącego węzła, które mają pasujący XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Wybiera wszystkie węzły przodków bieżącego węzła, które mają określoną nazwę lokalną i identyfikator URI przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Wybiera wszystkie węzły potomne bieżącego węzła, które mają pasujący XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Wybiera wszystkie węzły potomne bieżącego węzła, które mają określoną nazwę lokalną i identyfikator URI przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Wybiera wszystkie węzły potomne (descendant) bieżącego węzła, które mają pasujący XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Wybiera wszystkie węzły potomne bieżącego węzła o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Wybiera pojedynczy węzeł w [XPathNavigator](./) przy użyciu określonego zapytania [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Wybiera pojedynczy węzeł w obiekcie [XPathNavigator](./) przy użyciu określonego zapytania [XPath](../) oraz obiektu [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) służącego do rozwiązywania prefiksów przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Wybiera pojedynczy węzeł w [XPathNavigator](./) przy użyciu określonego obiektu [XPathExpression](../xpathexpression/). |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Ustawia znacznik reprezentujący węzły potomne bieżącego węzła. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Ustawia znacznik reprezentujący otwierające i zamykające znaczniki bieżącego węzła oraz jego węzłów potomnych. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Ustawia typowaną wartość bieżącego węzła. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Ustawia wartość bieżącego węzła. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca wartość tekstową bieżącego węzła. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Zwraca wartość bieżącego węzła jako określony typ, używając obiektu [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) służącego do rozwiązywania prefiksów przestrzeni nazw. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Zwraca wartość elementu jako określony typ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Strumieniuje bieżący węzeł i jego węzły potomne do określonego obiektu [XmlWriter](../../system.xml/xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |
## Zobacz także

* Klasa [XPathItem](../xpathitem/)
* Klasa [IXPathNavigable](../ixpathnavigable/)
* Klasa [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml::XPath](../)
* Biblioteka [Aspose.Slides](../../)