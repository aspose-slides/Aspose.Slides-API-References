---
title: XmlSchemaAny
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje element any konsorcjum World Wide Web (W3C).
type: docs
weight: 131
url: /pl/system.xml.schema/xmlschemaany/
---
## Klasa XmlSchemaAny


Reprezentuje element **any** konsorcjum World Wide [Web](../../system.web/) (W3C).

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Zwraca własność **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Zwraca identyfikator typu string. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Zwraca numer wiersza w pliku, do którego odnosi się element **schema**. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Zwraca pozycję wiersza w pliku, do którego odnosi się element **schema**. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Zwraca maksymalną liczbę wystąpień cząstki. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Zwraca liczbę jako wartość string. Maksymalna liczba wystąpień cząstki. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Zwraca minimalną liczbę wystąpień cząstki. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Zwraca liczbę jako wartość string. Minimalna liczba wystąpień cząstki. |
| [String](../../system/string/) [get_Namespace](./get_namespace/)() | Zwraca przestrzenie nazw zawierające elementy, które mogą być użyte. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Zwraca XmlSerializerNamespaces do użycia z tym obiektem schematu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Zwraca rodzica tego [XmlSchemaObject](../xmlschemaobject/). |
| [XmlSchemaContentProcessing](../xmlschemacontentprocessing/) [get_ProcessContents](./get_processcontents/)() | Zwraca informacje o tym, jak aplikacja lub procesor XML powinien obsługiwać walidację dokumentów XML dla elementów określonych przez element **any**. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Zwraca lokalizację źródłową pliku, który załadował schemat. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Zwraca kwalifikowane atrybuty, które nie należą do docelowej przestrzeni nazw bieżącego schematu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia hashowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Ustawia własność **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Ustawia identyfikator string. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Ustawia numer wiersza w pliku, do którego odnosi się element **schema**. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Ustawia pozycję wiersza w pliku, do którego odnosi się element **schema**. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Ustawia maksymalną liczbę wystąpień cząstki. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Ustawia liczbę jako wartość string. Maksymalna liczba wystąpień cząstki. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Ustawia minimalną liczbę wystąpień cząstki. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Ustawia liczbę jako wartość string. Minimalna liczba wystąpień cząstki. |
| void [set_Namespace](./set_namespace/)(const [String](../../system/string/)\&) | Ustawia przestrzenie nazw zawierające elementy, które mogą być użyte. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Ustawia XmlSerializerNamespaces do użycia z tym obiektem schematu. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Ustawia rodzica tego [XmlSchemaObject](../xmlschemaobject/). |
| void [set_ProcessContents](./set_processcontents/)([XmlSchemaContentProcessing](../xmlschemacontentprocessing/)) | Ustawia informacje o tym, jak aplikacja lub procesor XML powinien obsługiwać walidację dokumentów XML dla elementów określonych przez element **any**. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Ustawia lokalizację źródłową pliku, który załadował schemat. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Ustawia kwalifikowane atrybuty, które nie należą do docelowej przestrzeni nazw bieżącego schematu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-argument szablonu jako wskaźnik słaby (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlSchemaAny](./xmlschemaany/)() | Inicjalizuje nową instancję klasy [XmlSchemaAny](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicjalizuje nową instancję klasy [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Inicjalizuje nową instancję klasy [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typu

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |

## Uwagi



Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. 

## Zobacz też

* Klasa [XmlSchemaParticle](../xmlschemaparticle/)
* Przestrzeń nazw [System::Xml::Schema](../)
* Biblioteka [Aspose.Slides](../../)