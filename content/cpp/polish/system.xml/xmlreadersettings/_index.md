---
title: XmlReaderSettings
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa zestaw funkcji obsługiwanych przez obiekt XmlReader tworzony metodą XmlReader::Create."
type: docs
weight: 443
url: /pl/system.xml/xmlreadersettings/
---
## Klasa XmlReaderSettings

Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Tworzy kopię wystąpienia [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Zwraca wartość wskazującą, czy przeprowadzać sprawdzanie znaków. |
| **bool** [get_CloseInput](./get_closeinput/)() | Zwraca wartość wskazującą, czy podstawowy strumień lub TextReader powinny być zamknięte po zamknięciu czytnika. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Zwraca poziom zgodności, którego będzie przestrzegać [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Zwraca wartość określającą przetwarzanie DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Zwraca wartość wskazującą, czy ignorować komentarze. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Zwraca wartość wskazującą, czy ignorować instrukcje przetwarzania. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Zwraca wartość wskazującą, czy ignorować nieistotne białe znaki. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Zwraca offset numeru linii obiektu [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Zwraca offset pozycji linii obiektu [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Zwraca wartość wskazującą maksymalną dopuszczalną liczbę znaków w dokumencie powstałych w wyniku rozszerzania encji. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Zwraca wartość wskazującą maksymalną dopuszczalną liczbę znaków w dokumencie XML. Wartość zero (0) oznacza brak ograniczeń rozmiaru dokumentu XML. Wartość różna od zera określa maksymalny rozmiar w znakach. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Zwraca [XmlNameTable](../xmlnametable/) używany do atomowych porównań łańcuchów. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Zwraca wartość wskazującą, czy zakazać przetwarzania definicji typu dokumentu (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Zwraca XmlSchemaSet używany przy walidacji schematu. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Zwraca wartość określającą ustawienia walidacji schematu. To ustawienie ma zastosowanie do obiektów [XmlReader](../xmlreader/) walidujących schematy (wartość [XmlReaderSettings::get_ValidationType](./get_validationtype/) to [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Zwraca wartość wskazującą, czy [XmlReader](../xmlreader/) będzie przeprowadzać walidację lub przypisanie typu podczas odczytu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołuj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [Reset](./reset/)() | Resetuje członków klasy ustawień do ich wartości domyślnych. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Ustawia wartość wskazującą, czy przeprowadzać sprawdzanie znaków. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Ustawia wartość wskazującą, czy podstawowy strumień lub TextReader powinny być zamknięte po zamknięciu czytnika. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Ustawia poziom zgodności, którego będzie przestrzegać [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Ustawia wartość określającą przetwarzanie DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Ustawia wartość wskazującą, czy ignorować komentarze. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Ustawia wartość wskazującą, czy ignorować instrukcje przetwarzania. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Ustawia wartość wskazującą, czy ignorować nieistotne białe znaki. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Ustawia offset numeru linii obiektu [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Ustawia offset pozycji linii obiektu [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Ustawia wartość wskazującą maksymalną dopuszczalną liczbę znaków w dokumencie powstałych w wyniku rozszerzania encji. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Ustawia wartość wskazującą maksymalną dopuszczalną liczbę znaków w dokumencie XML. Wartość zero (0) oznacza brak ograniczeń rozmiaru dokumentu XML. Wartość różna od zera określa maksymalny rozmiar w znakach. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Ustawia [XmlNameTable](../xmlnametable/) używany do atomowych porównań łańcuchów. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Ustawia wartość wskazującą, czy zakazać przetwarzania definicji typu dokumentu (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Ustawia XmlSchemaSet używany przy walidacji schematu. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Ustawia wartość określającą ustawienia walidacji schematu. To ustawienie ma zastosowanie do obiektów [XmlReader](../xmlreader/) walidujących schematy (wartość [XmlReaderSettings::get_ValidationType](./get_validationtype/) to [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Ustawia wartość wskazującą, czy [XmlReader](../xmlreader/) będzie przeprowadzać walidację lub przypisanie typu podczas odczytu. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Ustawia [XmlResolver](../xmlresolver/) używany do dostępu do dokumentów zewnętrznych. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołuj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Dodaje obsługę zdarzenia, które występuje, gdy czytnik napotka błędy walidacji. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Usuwa obsługę zdarzenia, które występuje, gdy czytnik napotka błędy walidacji. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego używaj inteligentnych wskaźników lub ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Inicjalizuje nową instancję klasy [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla inteligentnego wskaźnika do instancji tej klasy. |

## Uwagi

Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani za pomocą operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)