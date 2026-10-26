---
title: XmlTextWriter
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje obiekt, który zapewnia szybki, niebuforowany, jednokierunkowy sposób generowania strumieni lub plików zawierających dane XML zgodne ze standardem W3C Extensible Markup Language (XML) 1.0 oraz zaleceniami Namespaces in XML.
type: docs
weight: 521
url: /pl/system.xml/xmltextwriter/
---
## XmlTextWriter klasa

Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Close](./close/)() override | Zamyka ten strumień i podłączony strumień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonej nazwy pliku. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu nazwy pliku i obiektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonego strumienia. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu strumienia i obiektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonego TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu TextWriter i obiektów [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonego [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu obiektów [Text::StringBuilder](../../system.text/stringbuilder/) i [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonego obiektu [XmlWriter](../xmlwriter/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](../xmlwriter/) przy użyciu określonych obiektów [XmlWriter](../xmlwriter/) i [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](../xmlwriter/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [Flush](./flush/)() override | Zrzuca zawartość bufora do podłączonych strumieni i również zrzuca podłączony strumień. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Zwraca podłączony obiekt strumienia. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Wskazuje, w jaki sposób formatowany jest wynik. |
| **int32_t** [get_Indentation](./get_indentation/)() | Zwraca liczbę znaków wcięcia (IndentChars) do zapisania dla każdego poziomu w hierarchii, gdy [XmlTextWriter::set_Formatting](./set_formatting/) ma wartość [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | Zwraca znak używany do wcięcia, gdy [XmlTextWriter::set_Formatting](./set_formatting/) ma wartość [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | Zwraca wartość wskazującą, czy włączyć obsługę przestrzeni nazw. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Zwraca znak używany do cytowania wartości atrybutów. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Zwraca obiekt [XmlWriterSettings](../xmlwritersettings/) używany do stworzenia tej instancji [XmlWriter](../xmlwriter/). |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Zwraca stan writera. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Zwraca bieżący zakres **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Zwraca XmlSpace reprezentujący bieżący zakres **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Zwraca najbliższy prefiks zdefiniowany w bieżącym zakresie przestrzeni nazw dla URI przestrzeni nazw. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Wskazuje, w jaki sposób formatowany jest wynik. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | Ustawia liczbę znaków wcięcia (IndentChars) dla każdego poziomu w hierarchii, gdy [XmlTextWriter::set_Formatting](./set_formatting/) ma wartość [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | Ustawia znak używany do wcięcia, gdy [XmlTextWriter::set_Formatting](./set_formatting/) ma wartość [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ustawia wartość wskazującą, czy włączyć obsługę przestrzeni nazw. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Ustawia znak używany do cytowania wartości atrybutów. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Gdy nadpisane w klasie pochodnej, zapisuje wszystkie atrybuty znalezione w bieżącej pozycji w [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy nadpisane w klasie pochodnej, zapisuje atrybut o określonej nazwie lokalnej, URI przestrzeni nazw i wartości. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy nadpisane w klasie pochodnej, zapisuje atrybut o określonej nazwie lokalnej i wartości. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy nadpisane w klasie pochodnej, zapisuje atrybut o określonym prefiksie, nazwie lokalnej, URI przestrzeni nazw i wartości. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Koduje podane bajty binarne jako base64 i zapisuje otrzymany tekst. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Koduje podane bajty binarne jako binhex i zapisuje otrzymany tekst. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Zapisuje blok **...** zawierający podany tekst. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Wymusza generowanie encji znakowej dla podanej wartości znaku Unicode. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Zapisuje tekst bufor po buforze. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Zapisuje komentarz **** zawierający podany tekst. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapisuje deklarację DOCTYPE z podaną nazwą i opcjonalnymi atrybutami. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element o określonej nazwie lokalnej i wartości. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element o określonej nazwie lokalnej, URI przestrzeni nazw i wartości. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element o określonym prefiksie, nazwie lokalnej, URI przestrzeni nazw i wartości. |
| void [WriteEndAttribute](./writeendattribute/)() override | Zamyka poprzednie wywołanie [XmlTextWriter::WriteStartAttribute](./writestartattribute/). |
| void [WriteEndDocument](./writeenddocument/)() override | Zamyka wszystkie otwarte elementy lub atrybuty i przywraca writer do stanu Start. |
| void [WriteEndElement](./writeendelement/)() override | Zamyka jeden element i usuwa odpowiadający zakres przestrzeni nazw. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Zapisuje odwołanie do encji jako **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | Zamyka jeden element i usuwa odpowiadający zakres przestrzeni nazw. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Zapisuje podaną nazwę, zapewniając, że jest prawidłowa według [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Zapisuje podaną nazwę, zapewniając, że jest prawidłowym **NmToken** według [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Gdy nadpisane w klasie pochodnej, kopiuje wszystko z czytnika do writera i przesuwa czytnik na początek następnego elementu. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopiuje wszystko z obiektu XPathNavigator do writera. Pozycja XPathNavigator pozostaje niezmieniona. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | Zapisuje instrukcję przetwarzania z odstępem między nazwą a tekstem, np. **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapisuje nazwę kwalifikowaną przestrzenią nazw. Metoda wyszukuje prefiks obowiązujący dla danej przestrzeni nazw. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Zapisuje surowy markup ręcznie z bufora znaków. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Zapisuje surowy markup ręcznie z łańcucha znaków. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapisuje początek atrybutu. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje początek atrybutu o określonej nazwie lokalnej i URI przestrzeni nazw. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Zapisuje początek atrybutu o określonej nazwie lokalnej. |
| void [WriteStartDocument](./writestartdocument/)() override | Zapisuje deklarację XML z wersją "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Zapisuje deklarację XML z wersją "1.0" oraz atrybutem standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Zapisuje podany znacznik początkowy i powiązuje go z podaną przestrzenią nazw oraz prefiksem. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy nadpisane w klasie pochodnej, zapisuje podany znacznik początkowy i powiązuje go z podaną przestrzenią nazw. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Gdy nadpisane w klasie pochodnej, zapisuje znacznik początkowy o określonej nazwie lokalnej. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Zapisuje podany tekst. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Generuje i zapisuje encję znakową surrogatową dla pary znaków surrogatowych. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Zapisuje wartość obiektu. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | Zapisuje wartość [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | Zapisuje wartość [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | Zapisuje wartość [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Zapisuje wartość [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | Zapisuje wartość [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Zapisuje liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | Zapisuje wartość [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | Zapisuje wartość [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | Zapisuje wartość [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Zapisuje podaną białą spację. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Tworzy instancję klasy [XmlTextWriter](./) przy użyciu określonego strumienia i kodowania. |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Tworzy instancję klasy [XmlTextWriter](./) przy użyciu określonego pliku. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Tworzy instancję klasy [XmlTextWriter](./) przy użyciu określonego TextWriter. |
| virtual  [~Object](../../system/object/~object/)() | Zniszcza obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Uwagi

Zaleca się użycie klasy [XmlWriter](../xmlwriter/) zamiast tego. 

Obiekty tej klasy powinny być alokowane wyłącznie przy pomocy funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

## Zobacz także

* Klasa [XmlWriter](../xmlwriter/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)