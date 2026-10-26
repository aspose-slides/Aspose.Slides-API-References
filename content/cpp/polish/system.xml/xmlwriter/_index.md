---
title: XmlWriter
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje obiekt, który zapewnia szybki, niebuforowany, jednokierunkowy sposób generowania strumieni lub plików zawierających dane XML.
type: docs
weight: 573
url: /pl/system.xml/xmlwriter/
---
## XmlWriter klasa

Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [Close](./close/)() | Gdy jest przesłonięta w klasie pochodnej, zamyka ten strumień i leżący pod spodem strumień. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Tworzy nową instancję [XmlWriter](./) używając podanej nazwy pliku. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](./) przy użyciu nazwy pliku i obiektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Tworzy nową instancję [XmlWriter](./) używając określonego strumienia. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](./) przy użyciu strumienia i obiektu [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Tworzy nową instancję [XmlWriter](./) używając określonego TextWriter. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](./) przy użyciu TextWriter i obiektów [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Tworzy nową instancję [XmlWriter](./) używając określonego [Text::StringBuilder](../../system.text/stringbuilder/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](./) przy użyciu obiektów [Text::StringBuilder](../../system.text/stringbuilder/) i [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Tworzy nową instancję [XmlWriter](./) używając określonego obiektu [XmlWriter](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Tworzy nową instancję [XmlWriter](./) przy użyciu określonych obiektów [XmlWriter](./) i [XmlWriterSettings](../xmlwritersettings/). |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżącą instancję klasy [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Flush](./flush/)() | Gdy jest przesłonięta w klasie pochodnej, opróżnia zawartość bufora do leżących pod spodem strumieni oraz opróżnia także leżący pod spodem strumień. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Zwraca obiekt [XmlWriterSettings](../xmlwritersettings/) użyty do utworzenia tej instancji [XmlWriter](./). |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Gdy jest przesłonięta w klasie pochodnej, pobiera stan piszącego. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Gdy jest przesłonięta w klasie pochodnej, pobiera bieżący zakres **xml:lang**. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Gdy jest przesłonięta w klasie pochodnej, pobiera XmlSpace reprezentujący bieżący zakres **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Gdy jest przesłonięta w klasie pochodnej, zwraca najbliższy prefiks zdefiniowany w bieżącym zakresie przestrzeni nazw dla URI przestrzeni nazw. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Gdy jest przesłonięta w klasie pochodnej, zapisuje wszystkie atrybuty znalezione w bieżącej pozycji w [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje atrybut z określoną nazwą lokalną, URI przestrzeni nazw i wartością. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje atrybut z określoną nazwą lokalną i wartością. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje atrybut z określonym prefiksem, nazwą lokalną, URI przestrzeni nazw i wartością. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Gdy jest przesłonięta w klasie pochodnej, koduje podane bajty binarne jako Base64 i zapisuje powstały tekst. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Gdy jest przesłonięta w klasie pochodnej, koduje podane bajty binarne jako **BinHex** i zapisuje powstały tekst. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Gdy jest przesłonięta w klasie pochodnej, zapisuje blok **...** zawierający określony tekst. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Gdy jest przesłonięta w klasie pochodnej, wymusza generowanie jednostki znakowej dla określonej wartości znaku Unicode. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Gdy jest przesłonięta w klasie pochodnej, zapisuje tekst w partiach bufora. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Gdy jest przesłonięta w klasie pochodnej, zapisuje komentarz **** zawierający określony tekst. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje deklarację DOCTYPE z określoną nazwą i opcjonalnymi atrybutami. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element z określoną nazwą lokalną i wartością. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element z określoną nazwą lokalną, URI przestrzeni nazw i wartością. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje element z określonym prefiksem, nazwą lokalną, URI przestrzeni nazw i wartością. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Gdy jest przesłonięta w klasie pochodnej, zamyka poprzednie wywołanie XmlWriter::WriteStartAttribute(String,String). |
| virtual void [WriteEndDocument](./writeenddocument/)() | Gdy jest przesłonięta w klasie pochodnej, zamyka wszystkie otwarte elementy lub atrybuty i przywraca piszącego do stanu Start. |
| virtual void [WriteEndElement](./writeendelement/)() | Gdy jest przesłonięta w klasie pochodnej, zamyka jeden element i usuwa odpowiadający zakres przestrzeni nazw. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje odwołanie do jednostki jako **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Gdy jest przesłonięta w klasie pochodnej, zamyka jeden element i usuwa odpowiadający zakres przestrzeni nazw. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje określoną nazwę, zapewniając, że jest ona prawidłową nazwą zgodnie z rekomendacją W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje określoną nazwę, zapewniając, że jest ona prawidłowym NmToken zgodnie z rekomendacją W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Gdy jest przesłonięta w klasie pochodnej, kopiuje wszystko z czytnika do piszącego i przesuwa czytnik na początek następnego elementu podrzędnego. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | Kopiuje wszystko z obiektu XPathNavigator do piszącego. Pozycja XPathNavigator pozostaje niezmieniona. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Gdy jest przesłonięta w klasie pochodnej, zapisuje instrukcję przetwarzania z odstępem między nazwą a tekstem w następujący sposób: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje nazwę kwalifikowaną przestrzenią nazw. Metoda ta wyszukuje prefiks obowiązujący dla danej przestrzeni nazw. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Gdy jest przesłonięta w klasie pochodnej, ręcznie zapisuje surowy znacznik z bufora znaków. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, ręcznie zapisuje surowy znacznik z łańcucha. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zapisuje początek atrybutu z określoną nazwą lokalną i URI przestrzeni nazw. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje początek atrybutu z określonym prefiksem, nazwą lokalną i URI przestrzeni nazw. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Zapisuje początek atrybutu z określoną nazwą lokalną. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Gdy jest przesłonięta w klasie pochodnej, zapisuje deklarację XML z wersją "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Gdy jest przesłonięta w klasie pochodnej, zapisuje deklarację XML z wersją "1.0" oraz atrybutem standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje określony znacznik początkowy i wiąże go z podaną przestrzenią nazw. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje określony znacznik początkowy i wiąże go z podaną przestrzenią nazw oraz prefiksem. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje znacznik początkowy z określoną nazwą lokalną. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Gdy jest przesłonięta w klasie pochodnej, zapisuje podany tekst. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Gdy jest przesłonięta w klasie pochodnej, generuje i zapisuje jednostkę znakową zastępczą dla pary znaków zastępczych. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Zapisuje wartość obiektu. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Zapisuje wartość [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | Zapisuje wartość [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Zapisuje wartość [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Zapisuje wartość [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | Zapisuje wartość [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | Zapisuje liczbę zmiennoprzecinkową pojedynczej precyzji. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Zapisuje wartość [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Zapisuje wartość [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Zapisuje wartość [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Gdy jest przesłonięta w klasie pochodnej, zapisuje podaną białą spację. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla wskaźnika współdzielonego do instancji tej klasy. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)