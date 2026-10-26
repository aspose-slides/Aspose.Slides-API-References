---
title: XmlWriterSettings
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa zestaw funkcji obsługiwanych przez obiekt XmlWriter utworzony metodą XmlWriter::Create."
type: docs
weight: 586
url: /pl/system.xml/xmlwritersettings/
---
## XmlWriterSettings klasa


Określa zestaw funkcji obsługiwanych przez obiekt [XmlWriter](../xmlwriter/) utworzony metodą [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Tworzy kopię instancji [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Zwraca wartość wskazującą, czy XML writer powinien sprawdzać, czy wszystkie znaki w dokumencie są zgodne z sekcją "2.2 Characters" W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Zwraca wartość wskazującą, czy [XmlWriter](../xmlwriter/) powinien również zamykać podstawowy strumień lub TextWriter po wywołaniu metody [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Zwraca poziom zgodności, dla którego XML writer sprawdza wyjściowy XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Zwraca wartość wskazującą, czy [XmlWriter](../xmlwriter/) nie enkoduje atrybutów URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Zwraca typ kodowania tekstu do użycia. |
| **bool** [get_Indent](./get_indent/)() | Zwraca wartość wskazującą, czy wcięcia elementów są włączone. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Zwraca ciąg znaków używany przy wcięciach. To ustawienie jest używane, gdy wartość [XmlWriterSettings::set_Indent](./set_indent/) jest ustawiona na **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Zwraca wartość wskazującą, czy [XmlWriter](../xmlwriter/) powinien usuwać zduplikowane deklaracje przestrzeni nazw przy zapisie XML. Domyślne zachowanie to wypisywanie wszystkich deklaracji przestrzeni nazw obecnych w resolverze przestrzeni nazw writera. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Zwraca ciąg znaków używany do znaków końca linii. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Zwraca wartość wskazującą, czy normalizować znaki końca linii w wyjściu. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Zwraca wartość wskazującą, czy pisać atrybuty w nowej linii. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Zwraca wartość wskazującą, czy pomijać deklarację XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Zwraca metodę używaną do serializacji wyjścia [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Zwraca wartość wskazującą, czy [XmlWriter](../xmlwriter/) doda tagi zamykające do wszystkich niezamkniętych tagów elementów po wywołaniu metody [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [Reset](./reset/)() | Resetuje pola klasy ustawień do wartości domyślnych. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Ustawia wartość wskazującą, czy XML writer powinien sprawdzać, czy wszystkie znaki w dokumencie są zgodne z sekcją "2.2 Characters" W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Ustawia wartość wskazującą, czy [XmlWriter](../xmlwriter/) powinien również zamykać podstawowy strumień lub TextWriter po wywołaniu metody [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Ustawia poziom zgodności, dla którego XML writer sprawdza wyjściowy XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Ustawia wartość wskazującą, czy [XmlWriter](../xmlwriter/) nie enkoduje atrybutów URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Ustawia typ kodowania tekstu do użycia. |
| void [set_Indent](./set_indent/)(**bool**) | Ustawia wartość wskazującą, czy wcięcia elementów są włączone. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Ustawia ciąg znaków używany przy wcięciach. To ustawienie jest używane, gdy wartość [XmlWriterSettings::set_Indent](./set_indent/) jest ustawiona na **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Ustawia wartość wskazującą, czy [XmlWriter](../xmlwriter/) powinien usuwać zduplikowane deklaracje przestrzeni nazw przy zapisie XML. Domyślne zachowanie to wypisywanie wszystkich deklaracji przestrzeni nazw obecnych w resolverze writera. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Ustawia ciąg znaków używany do znaków końca linii. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Ustawia wartość wskazującą, czy normalizować znaki końca linii w wyjściu. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Ustawia wartość wskazującą, czy zapisywać atrybuty w nowej linii. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Ustawia wartość wskazującą, czy pomijać deklarację XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Ustawia wartość wskazującą, czy [XmlWriter](../xmlwriter/) doda tagi zamykające do wszystkich niezamkniętych tagów elementów po wywołaniu metody [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | Inicjalizuje nową instancję klasy [XmlWriterSettings](./). |
| virtual [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Uwagi

Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. 

## Zobacz również

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)