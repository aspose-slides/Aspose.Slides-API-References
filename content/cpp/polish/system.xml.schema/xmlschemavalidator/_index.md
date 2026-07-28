---
title: XmlSchemaValidator
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje silnik walidacji schematu XML Schema Definition Language (XSD). Klasa XmlSchemaValidator nie może być dziedziczona.
type: docs
weight: 937
url: /pl/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator klasa

Represents an XML [Schema](../) Definition Language (XSD) [Schema](../) validation engine. The [XmlSchemaValidator](./) class cannot be inherited.

```cpp
class XmlSchemaValidator : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Dodaje schemat XML [Schema](../) Definition Language (XSD) do zestawu schematów używanych do walidacji. |
| void [EndValidation](./endvalidation/)() | Kończy walidację i sprawdza ograniczenia tożsamości dla całego dokumentu XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | Zwraca informację o numerze wiersza dla walidowanego węzła XML. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | Zwraca źródłowy URI dla walidowanego węzła XML. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | Zwraca obiekt wysłany jako obiekt nadawcy zdarzenia walidacji. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | Zwraca oczekiwane atrybuty dla bieżącego kontekstu elementu. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | Zwraca oczekiwane cząstki w bieżącym kontekście elementu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | Waliduje ograniczenia tożsamości na domyślnych atrybutach i wypełnia podaną Listę obiektami [XmlSchemaAttribute](../xmlschemaattribute/) dla wszelkich atrybutów z wartościami domyślnymi, które nie zostały wcześniej zwalidowane przy użyciu metody [XmlSchemaValidator::ValidateAttribute](./validateattribute/) w kontekście elementu. |
| void [Initialize](./initialize/)() | Inicjalizuje stan obiektu [XmlSchemaValidator](./). |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Inicjalizuje stan obiektu [XmlSchemaValidator](./) przy użyciu określonego [XmlSchemaObject](../xmlschemaobject/) do częściowej walidacji. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia kopiowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | Ustawia informację o numerze wiersza dla walidowanego węzła XML. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Ustawia źródłowy URI dla walidowanego węzła XML. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Ustawia obiekt wysyłany jako obiekt nadawcy zdarzenia walidacji. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Ustawia obiekt [XmlResolver](../../system.xml/xmlresolver/) używany do rozwiązywania elementów **xs:import** i **xs:include** oraz atrybutów **xsi:schemaLocation** i **xsi:noNamespaceSchemaLocation**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Pomija walidację bieżącej zawartości elementu i przygotowuje obiekt [XmlSchemaValidator](./) do walidacji zawartości w kontekście elementu nadrzędnego. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Waliduje nazwę atrybutu, URI przestrzeni nazw oraz wartość w bieżącym kontekście elementu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Waliduje nazwę atrybutu, URI przestrzeni nazw oraz wartość w bieżącym kontekście elementu. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Waliduje element w bieżącym kontekście. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Waliduje element w bieżącym kontekście z określonymi wartościami atrybutów **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** oraz **xsi:NoNamespaceSchemaLocation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Sprawdza, czy zawartość tekstowa elementu jest prawidłowa względem jego typu danych dla elementów o prostych treściach oraz czy zawartość bieżącego elementu jest kompletna dla elementów o złożonych treściach. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Sprawdza, czy zawartość tekstowa wskazanego elementu jest prawidłowa względem jego typu danych. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Sprawdza, czy wszystkie wymagane atrybuty w kontekście elementu są obecne i przygotowuje obiekt [XmlSchemaValidator](./) do walidacji zawartości podrzędnej elementu. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | Waliduje, czy podany **string** tekstowy jest dozwolony w bieżącym kontekście elementu i gromadzi tekst do walidacji, jeśli element ma prostą treść. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | Waliduje, czy tekst zwracany przez wskazany obiekt XmlValueGetter jest dozwolony w bieżącym kontekście elementu i gromadzi tekst do walidacji, jeśli element ma prostą treść. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | Waliduje, czy biały znak w podanym **string** jest dozwolony w bieżącym kontekście elementu i gromadzi biały znak do walidacji, jeśli element ma prostą treść. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | Waliduje, czy biały znak zwracany przez wskazany obiekt XmlValueGetter jest dozwolony w bieżącym kontekście elementu i gromadzi biały znak do walidacji, jeśli element ma prostą treść. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | Inicjalizuje nową instancję klasy [XmlSchemaValidator](./). |
| virtual  [~Object](../../system/object/~object/)() | Zniszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Uwagi

Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to powodować błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Xml::Schema](../)
* Biblioteka [Aspose.Slides](../../)