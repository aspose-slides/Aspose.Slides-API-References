---
title: ConsoleOutput
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Representuje standardowy strumień wyjściowy. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik System::SmartPtr i użyj tego wskaźnika do przekazywania jej funkcjom jako argument."
type: docs
weight: 209
url: /pl/system/consoleoutput/
---
## ConsoleOutput klasa


Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Zamyka strumień i zwalnia pozyskane zasoby. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka leżący pod nim strumień. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Opróżnia zawartość bufora do leżącego pod nim strumienia. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Zawsze zwraca kodowanie ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Zwraca aktualnie używany obiekt [IFormatProvider](../iformatprovider/). |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Zwraca aktualnie używany obiekt [IFormatProvider](../iformatprovider/). |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Zwraca ciąg znaków końca linii. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Zwraca ciąg znaków końca linii. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartowniczego [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Ustawia ciąg znaków końca linii. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala zmienić wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartowniczego [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Write](./write/)(**bool**) override | Wypisuje reprezentację tekstową podanej wartości bool na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Wypisuje reprezentację tekstową podanego obiektu na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(char_t) override | Wypisuje podany znak na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)([Decimal](../decimal/)) override | Wypisuje reprezentację tekstową wartości [Decimal](../decimal/) na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**double**) override | Wypisuje reprezentację tekstową podwójnej precyzji liczby zmiennoprzecinkowej na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**int32_t**) override | Wypisuje reprezentację tekstową 32-bitowej wartości całkowitej na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**int64_t**) override | Wypisuje reprezentację tekstową 64-bitowej wartości całkowitej na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**float**) override | Wypisuje reprezentację tekstową liczby zmiennoprzecinkowej pojedynczej precyzji na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const [String](../string/)\&) override | Wypisuje podany obiekt ciągu znaków na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**uint32_t**) override | Wypisuje reprezentację tekstową 32-bitowej liczby całkowitej bez znaku na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(**uint64_t**) override | Wypisuje reprezentację tekstową 64-bitowej liczby całkowitej bez znaku na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Wypisuje reprezentację tekstową podanej tablicy znaków na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Wypisuje reprezentację tekstową zakresu wartości podanej tablicy znaków na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const char_t *) override | Wypisuje podany c-string na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Wypisuje reprezentację tekstową podanego obiektu [TypeInfo](../typeinfo/) na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Zapisuje reprezentację tekstową podanej 32-bitowej wartości całkowitej do strumienia. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane zgodnie z podanym formatem do strumienia. |
| void [WriteLine](./writeline/)() override | Wypisuje bieżący znak końca linii na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Wypisuje reprezentację tekstową podanego obiektu, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**bool**) override | Wypisuje reprezentację tekstową podanej wartości bool, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(char_t) override | Wypisuje podany znak, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Wypisuje reprezentację tekstową wartości [Decimal](../decimal/), po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**double**) override | Wypisuje reprezentację tekstową podwójnej precyzji liczby zmiennoprzecinkowej, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(int) override | Wypisuje reprezentację tekstową 32-bitowej wartości całkowitej, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**int64_t**) override | Wypisuje reprezentację tekstową 64-bitowej wartości całkowitej, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**float**) override | Wypisuje reprezentację tekstową liczby zmiennoprzecinkowej pojedynczej precyzji, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Wypisuje podany obiekt ciągu znaków, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Wypisuje reprezentację tekstową 32-bitowej liczby całkowitej bez znaku, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Wypisuje reprezentację tekstową 64-bitowej liczby całkowitej bez znaku, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Wypisuje reprezentację tekstową podanej tablicy znaków, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Wypisuje reprezentację tekstową zakresu wartości podanej tablicy znaków, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const char_t *) override | Wypisuje podany c-string, po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Wypisuje reprezentację tekstową podanego obiektu [TypeInfo](../typeinfo/), po czym dodaje bieżący znak końca linii, na strumień wyjściowy reprezentowany przez bieżący obiekt. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Zapisuje podane wartości sformatowane zgodnie z podanym formatem, a następnie znaki końca linii, do strumienia. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destruktor. |
## Zobacz także

* Klasa [TextWriter](../../system.io/textwriter/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)