---
title: String
second_title: Referencja API Aspose.Slides dla C++
description: "Klasa String używana w całej bibliotece. Jest zamiennikiem dla C# System.String przy tłumaczeniu kodu. Ze względu na optymalizację nie jest traktowana jako podklasa Object. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1275
url: /pl/system/string/
---
## Klasa String

[String](./) klasa używana w całej bibliotece. Jest zamiennikiem dla C# [System.String](./) przy tłumaczeniu kodu. Z powodów optymalizacji nie jest uważana za podklasę [Object](../object/). Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
class String
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) jest typem wartości po stronie C++, który domyślnie (bez dziedziczenia) implementuje niektóre interfejsy. |
| const UChar * [begin](./begin/)() const | Zwraca wskaźnik na początek rzeczywistego bufora ciągu. Nigdy nie realokuje niczego. Nie gwarantuje, że bufor jest zakończony znakiem null. |
| [String](./) [Clone](./clone/)() const | Tworzy kopię bieżącego ciągu. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Porównuje dwa podciągi według kolejności mniej-równe-więcej. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Porównuje dwa podciągi według kolejności mniej-równe-więcej. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Porównuje dwa ciągi według kolejności mniej-równe-więcej. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Porównuje dwa ciągi według kolejności mniej-równe-więcej. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Porównuje dwa ciągi według kolejności mniej-równe-więcej. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Porównuje dwa ciągi według kolejności mniej-równe-więcej. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Porównuje dwa ciągi używając trybu porządkowego. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Porównuje dwa ciągi używając trybu porządkowego. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Porównuje dwa ciągi w stylu 'mniej-równe-więcej'. Używa bieżącej kultury. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Łączy ciągi. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Łączy ciągi. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Łączy ciągi. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Łączy ciągi. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Sprawdza, czy str jest podciągiem bieżącego ciągu. |
| **bool** [Contains](./contains/)(char16_t) const | Sprawdza, czy ciąg zawiera podany znak. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Tworzy kopię ciągu. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Kopiuje znaki ciągu do istniejących elementów tablicy. Nie wykonuje zmiany rozmiaru. |
| const UChar * [end](./end/)() const | Zwraca wskaźnik na koniec rzeczywistego bufora ciągu. Nigdy nie realokuje niczego. Nie gwarantuje, że bufor jest zakończony znakiem null. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Sprawdza, czy ciąg kończy się podanym podciągiem. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Sprawdza, czy ciąg kończy się podanym podciągiem. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Sprawdza, czy ciąg kończy się podanym podciągiem. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) porównanie równości. Wspierane są różne tryby dostarczane przez wyliczenie StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) porównanie równości. Używa trybu porównania [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Porównuje dwa ciągi przy użyciu trybu porównania porządkowego. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Porównuje dwa ciągi. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Próbuje przekonwertować [String](./) na ciąg ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formatuje ciąg w stylu C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formatuje ciąg w stylu C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formatuje ciąg w stylu C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formatuje ciąg w stylu C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formatuje ciąg w stylu C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Tworzy [String](./) z ciągu ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Tworzy [String](./) z ciągu ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Tworzy [String](./) z ciągu ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Tworzy [String](./) z ciągu utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Tworzy [String](./) z ciągu utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Tworzy [String](./) z ciągu utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Tworzy [String](./) z ciągu utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Tworzy [String](./) z ciągu utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Tworzy [String](./) z ciągu utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Tworzy [String](./) z ciągu wide. |
| int [get_Length](./get_length/)() const | Zwraca długość ciągu. |
| int [GetHashCode](./gethashcode/)() const | Oblicza hash zawartego ciągu. Zrealizowane w ICU, nie jest zgodny z hashami w C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Wyszukiwanie podciągu naprzód. |
| int [IndexOf](./indexof/)(char_t, int) const | Wyszukiwanie znaku naprzód. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Wyszukiwanie znaku w podciągu naprzód. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Wyszukiwanie podciągu naprzód. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Wyszukiwanie podciągu naprzód. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Wyszukiwanie podciągu naprzód. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Wyszukiwanie podciągu naprzód. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Wyszukiwanie znaku naprzód. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Przegląda wszystkie znaki str w kolejności; jeśli znajdzie pierwszy znak, zwraca jego pozycję, w przeciwnym razie szuka kolejnego. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Wyszukuje dowolny z podanych znaków w całym ciągu. Porównuje pierwszy znak ciągu ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego dopasowanego znaku. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Wyszukuje dowolny z podanych znaków w podciągu. Porównuje pierwszy znak ciągu ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego dopasowanego znaku. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Wyszukuje dowolny z podanych znaków w podciągu. Porównuje pierwszy znak ciągu ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego dopasowanego znaku. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Wstawia podciąg na określonej pozycji. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt ciągu jest typu określonego przez przekazany [TypeInfo](../typeinfo/). |
| **bool** [IsAsciiString](./isasciistring/)() const | Wskazuje, czy [String](./) zawiera wyłącznie symbole ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Sprawdza, czy ciąg nie jest nullem i jest pusty. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Sprawdza, czy ciąg Unicode jest znormalizowany przy użyciu podanej formy normalizacji. |
| **bool** [IsNull](./isnull/)() const | Sprawdza, czy ciąg jest uznawany za null. [String](./) jest nullem tylko wtedy, gdy został utworzony przy użyciu konstruktora [String()](./string/), przeniesiony, skopiowany lub przypisany z nullem lub wywołano metodę [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Sprawdza, czy ciąg jest pusty lub uznawany za null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Sprawdza, czy przekazany ciąg jest nullem lub pusty. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Wskazuje, czy określony ciąg jest nullem, pusty lub składa się wyłącznie ze znaków białych. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Łączy tablicę używając ciągu jako separatora. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Łączy tablicę używając ciągu jako separatora. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Łączy tablicę używając ciągu jako separatora. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Łączy tablicę używając ciągu jako separatora. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Wyszukiwanie wstecz podciągu. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Wyszukiwanie wstecz podciągu. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Wyszukiwanie wstecz podciągu. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Wyszukiwanie wstecz podciągu. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Wyszukiwanie wstecz znaku. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Wyszukiwanie wstecz znaku. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Wyszukiwanie wstecz znaku. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Wyszukuje dowolny z podanych znaków w całym ciągu w odwrotnej kolejności. Porównuje ostatni znak ciągu ze wszystkimi znakami w anyOf, potem poprzedni i tak dalej. Zwraca indeks pierwszego dopasowania. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Wyszukuje dowolny z podanych znaków w podciągu w odwrotnej kolejności. Porównuje ostatni znak ciągu ze wszystkimi znakami w anyOf, potem poprzedni i tak dalej. Zwraca indeks pierwszego dopasowania. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Wyszukuje dowolny z podanych znaków w podciągu w odwrotnej kolejności. Porównuje ostatni znak ciągu ze wszystkimi znakami w anyOf, potem poprzedni i tak dalej. Zwraca indeks pierwszego dopasowania. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalizuje ciąg Unicode przy użyciu podanej formy normalizacji. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Konwertuje ciąg na niezmienny span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operator nierówności. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Sprawdza, czy ciąg nie jest nullem. Stosuje tę samą logikę co wywołanie [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) operator konkatenacji. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) konkatenacja z literałem ciągu lub wskaźnikiem do ciągu znaków. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Dodaje znak na koniec ciągu. |
| [String](./) [operator+](./operator_plus/)(int) const | Dodaje reprezentację ciągu wartości całkowitej do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Dodaje reprezentację ciągu wartości całkowitej bez znaku do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Dodaje reprezentację ciągu wartości zmiennoprzecinkowej do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Dodaje reprezentację ciągu wartości całkowitej 64-bitowej do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Dodaje reprezentację ciągu obiektu typu referencyjnego do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Dodaje reprezentację ciągu obiektu typu referencyjnego do końca ciągu. |
| [String](./) [operator+](./operator_plus/)(T) const | Dodaje reprezentację ciągu wartości logicznej do końca ciągu. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operator przypisania konkatenacji. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operator przypisania konkatenacji. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Porównuje kolejność łańcuchów. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operator przypisania. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operator przypisania przenoszącego. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operator porównania równości. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Sprawdza, czy ciąg jest null. Zastosowuje taką samą logikę jak wywołanie [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Porównuje kolejność łańcuchów. |
| char_t [operator[]](./operator[]/)(int) const | Pobiera znak w określonej pozycji. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Dodaje wypełnienie po lewej stronie oryginalnego ciągu. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Dodaje wypełnienie po prawej stronie oryginalnego ciągu. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Zwraca iterator odwrócony do ostatniego znaku (jeśli istnieje) rzeczywistego bufora ciągu. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Wyodrębnia wszystko oprócz podciągu z bieżącego ciągu. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Zwraca iterator odwrócony do znaku przed pierwszym (jeśli istnieje) rzeczywistego bufora ciągu. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Zastępuje wszystkie wystąpienia znaku w ciągu. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Zastępuje wszystkie wystąpienia wyszukiwania w tym ciągu. |
| [String](./)& [reset](./reset/)() | Ustawia ciąg na null. Jest analogiczne do 'string_variable_name = null' w języku C#. |
| [String](./)& [SetCharAt](./setcharat/)(int, char_t) | Ustawia znak w określonej pozycji. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według znaku. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według znaku. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według jednego z dwóch znaków. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [ArrayPtr](../arrayptr/)<char_t>\&, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według jednego ze wskazanych znaków. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [ArrayPtr](../arrayptr/)<char_t>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według jednego ze wskazanych znaków. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według podciągu. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według podciągu. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [ArrayPtr](../arrayptr/)<[String](./)>\&, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według podciągu. |
| [ArrayPtr](../arrayptr/)<[String](./)> [Split](./split/)(const [ArrayPtr](../arrayptr/)<[String](./)>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Dzieli ciąg według podciągu. Obecnie obsługuje tylko tablicę separatorów o zerowej lub jednej pozycji. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Sprawdza, czy ciąg zaczyna się od określonego podciągu. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Sprawdza, czy ciąg zaczyna się od określonego podciągu. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)>\&) const | Sprawdza, czy ciąg zaczyna się od określonego podciągu. |
| [String](./string/)() | Konstruktor domyślny. Tworzy obiekt ciągu, który jest traktowany jako null. |
| [String](./string/)(T\&, typename std::enable_if<[IsStringLiteral](../isstringliteral/)<T, char16_t>::value>::type *) | Tworzy ciąg na podstawie literału łańcucha. Traktuje literał jako łańcuch zakończony znakiem null, oblicza docelową długość ciągu na podstawie rozmiaru literału. |
| [String](./string/)(const T\&, typename std::enable_if<[IsStringPointer](../isstringpointer/)<T, char16_t>::value>::type *) | Tworzy ciąg na podstawie wskaźnika na ciąg znakowy. Traktuje wskazany ciąg jako zakończony znakiem null, oblicza docelową długość ciągu na podstawie znaku null. |
| explicit [String](./string/)(T\&, typename std::enable_if<[IsStringLiteral](../isstringliteral/)<T, char>::value>::type *) | Tworzy ciąg na podstawie literału łańcucha. Traktuje literał jako łańcuch zakończony znakiem null w UTF-8, oblicza docelową długość ciągu na podstawie rozmiaru literału. |
| explicit [String](./string/)(const T\&, typename std::enable_if<[IsStringPointer](../isstringpointer/)<T, char>::value>::type *) | Tworzy ciąg na podstawie wskaźnika na ciąg znakowy. Traktuje wskazany ciąg jako zakończony znakiem null w UTF-8, oblicza docelową długość ciągu na podstawie znaku null. |
| [String](./string/)(const char16_t *, int) | Tworzy ciąg z wskaźnika na ciąg znakowy i podanej długości. |
| [String](./string/)(const [ReadOnlySpan](../readonlyspan/)<char16_t>\&) | Inicjalizuje nową instancję klasy [System.String](./) znakami Unicode wskazanymi w określonym niezmiennym zakresie. |
| [String](./string/)(const char *, int) | Tworzy ciąg z wskaźnika na ciąg znakowy i podanej długości. |
| [String](./string/)(const char16_t *, int, int) | Tworzy ciąg z wskaźnika na ciąg znakowy, zaczynając od podanej pozycji i używając długości. |
| explicit [String](./string/)(const char16_t, int) | Konstruktor wypełniający. |
| [String](./string/)(const T\&, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *) | Konstruktor nullptr. Zadeklarowany jako szablon w celu rozstrzygania priorytetów z innymi konstruktorami szablonowymi. |
| explicit [String](./string/)(T\&, typename std::enable_if<[IsStringLiteral](../isstringliteral/)<T, **wchar_t**>::value>::type *) | Tworzy ciąg na podstawie literału szerokiego łańcucha znaków. Traktuje literał jako łańcuch zakończony znakiem null, oblicza docelową długość ciągu na podstawie rozmiaru literału. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie zezwala się na konwersje niejawne. |
| explicit [String](./string/)(const T\&, typename std::enable_if<[IsStringPointer](../isstringpointer/)<T, **wchar_t**>::value>::type *) | Tworzy ciąg na podstawie wskaźnika na szeroki ciąg znaków. Traktuje wskazany ciąg jako zakończony znakiem null, oblicza docelową długość ciągu na podstawie znaku null. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie zezwala się na konwersje niejawne. |
| explicit [String](./string/)(const **wchar_t** *, int) | Tworzy ciąg z wskaźnika na szeroki ciąg znaków i podanej długości. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie zezwala się na konwersje niejawne. |
| explicit [String](./string/)(const **wchar_t**, int) | Konstruktor wypełniający. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie zezwala się na konwersje niejawne. |
| [String](./string/)(const [String](./)\&) | Konstruktor kopiujący. |
| [String](./string/)([String](./)\&&) | Konstruktor przenoszący. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)<char16_t>\&) | Konwertuje całą tablicę znaków na ciąg. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)<char16_t>\&, int, int) | Konwertuje podzakres tablicy znaków na ciąg. Jeśli parametry są poza zakresem tablicy, tworzony jest pusty ciąg. |
| explicit [String](./string/)(const codeporting_icu::UnicodeString\&) | Opakowuje UnicodeString w [String](./). |
| explicit [String](./string/)(codeporting_icu::UnicodeString&&) | Konstruktor przenoszący. |
| explicit [String](./string/)(const std::wstring\&) | Tworzy [String](./) z szerokiego ciągu znaków. |
| explicit [String](./string/)(const std::u16string\&) | Tworzy [String](./) z ciągu utf16. |
| explicit [String](./string/)(const std::string\&) | Tworzy [String](./) z std::string w formacie UTF-8. |
| explicit [String](./string/)(const std::u32string\&) | Tworzy [String](./) z std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Wyodrębnia podciąg. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Wyodrębnia podciąg. |
| std::string [ToAsciiString](./toasciistring/)() const | Konwertuje ciąg na std::string. Używa kodowania ASCII. |
| [ArrayPtr](../arrayptr/)<**uint8_t**> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Konwertuje ciąg lub podciąg na tablicę bajtów. |
| [ArrayPtr](../arrayptr/)<char_t> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Konwertuje ciąg lub podciąg na tablicę znaków. |
| [String](./) [ToLower](./tolower/)() const | Konwertuje wszystkie znaki ciągu na małe litery. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)>\&) const | Konwertuje wszystkie znaki ciągu na małe litery przy użyciu określonej kultury. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Konwertuje wszystkie znaki ciągu na małe litery przy użyciu kultury invariantnej. |
| [String](./) [ToString](./tostring/)() const | Opakowanie do obsługi klasy [String](./) w kontekstach, w których [ToString()](./tostring/) jest wywoływane na obiektach typu wartościowego. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)<[IFormatProvider](../iformatprovider/)>\&) const | Opakowanie do obsługi klasy [String](./) w kontekstach, w których [ToString()](./tostring/) jest wywoływane na obiektach typu wartościowego. |
| std::u16string [ToU16Str](./tou16str/)() const | Konwertuje ciąg na std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Konwertuje ciąg na std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Konwertuje wszystkie znaki ciągu na wielkie litery. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)>\&) const | Konwertuje wszystkie znaki ciągu na wielkie litery przy użyciu określonej kultury. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Konwertuje wszystkie znaki ciągu na wielkie litery przy użyciu kultury invariantnej. |
| std::string [ToUtf8String](./toutf8string/)() const | Konwertuje ciąg na std::string. Używa kodowania UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Konwertuje ciąg na std::wstring. |
| [String](./) [Trim](./trim/)() const | Usuwa wszystkie znaki białych odstępów z początku i końca ciągu. |
| [String](./) [Trim](./trim/)(char_t) const | Usuwa wszystkie wystąpienia podanego znaku z początku i końca ciągu. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Usuwa wszystkie wystąpienia podanych znaków z początku i końca ciągu. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)<char_t>\&) const | Usuwa wszystkie wystąpienia podanych znaków z początku i końca ciągu. |
| [String](./) [TrimEnd](./trimend/)() const | Usuwa wszystkie znaki białych odstępów z końca ciągu. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Usuwa wszystkie wystąpienia podanego znaku z końca ciągu. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Usuwa wszystkie wystąpienia podanych znaków z końca ciągu. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)<char_t>\&) const | Usuwa wszystkie wystąpienia podanych znaków z końca ciągu. |
| [String](./) [TrimStart](./trimstart/)() const | Usuwa wszystkie znaki białych odstępów z początku ciągu. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Usuwa wszystkie wystąpienia podanego znaku z początku ciągu. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Usuwa wszystkie wystąpienia podanych znaków z początku ciągu. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)<char_t>\&) const | Usuwa wszystkie wystąpienia podanych znaków z początku ciągu. |
| const UChar * [u_str](./u_str/)() const | Zwraca bufor zakończony znakiem null w stylu ICU. Może realokować ciąg. |
| [~String](./~string/)() | Destruktor. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | Pusty ciąg. |
| static [Null](./null/) | Ciąg null. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Typ iteratora odwróconego. |

## Uwagi

```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Utwórz łańcuch znaków z tablicy znaków i wypisz go.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Utwórz łańcuch znaków z tablicy bajtów i wypisz go.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Usuń nadmiarowe białe znaki z poniższego łańcucha i wypisz go.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Wypisz liczbę słów w .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujące wyjście:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)