---
title: String
second_title: Aspose.Slides für C++ API-Referenz
description: "String-Klasse, die in der gesamten Bibliothek verwendet wird. Sie ist ein Ersatz für C# System.String beim Übersetzen von Code. Aus Optimierungsgründen wird sie nicht als Unterklasse von Object betrachtet. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1275
url: /de/system/string/
---
## String-Klasse


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) ist ein Werttyp auf der C++-Seite, der implizit (ohne Vererbung) einige Schnittstellen implementiert. |
| const UChar * [begin](./begin/)() const | Gibt einen Zeiger auf den Beginn des aktuellen Zeichenfolgenpuffers zurück. Rekonstruiert niemals etwas. Garantiert nicht, dass der Puffer nullterminiert ist. |
| [String](./) [Clone](./clone/)() const | Erstelle eine Kopie der aktuellen Zeichenfolge. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Vergleicht zwei Teilzeichenfolgen nach dem Muster kleiner-gleich-größer. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Vergleicht zwei Zeichenfolgen nach dem Muster kleiner-gleich-größer im Ordinalmodus. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Vergleicht zwei Zeichenfolgen nach dem Muster kleiner-gleich-größer im Ordinalmodus. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Vergleicht zwei Zeichenfolgen im 'kleiner-gleich-größer'-Stil. Verwendet die aktuelle Kultur. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Verkettet Zeichenfolgen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Verkettet Zeichenfolgen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Verkettet Zeichenfolgen. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Verkettet Zeichenfolgen. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Prüft, ob str ein Teilstring der aktuellen Zeichenfolge ist. |
| **bool** [Contains](./contains/)(char16_t) const | Prüft, ob die Zeichenfolge das angegebene Zeichen enthält. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Erstellt eine Kopie der Zeichenfolge. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Kopiert Zeichen der Zeichenfolge in vorhandene Array-Elemente. Eine Größenänderung wird nicht durchgeführt. |
| const UChar * [end](./end/)() const | Gibt einen Zeiger auf das Ende des aktuellen Zeichenfolgenpuffers zurück. Rekonstruiert niemals etwas. Garantiert nicht, dass der Puffer nullterminiert ist. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Prüft, ob die Zeichenfolge mit dem angegebenen Teilstring endet. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Prüft, ob die Zeichenfolge mit dem angegebenen Teilstring endet. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Prüft, ob die Zeichenfolge mit dem angegebenen Teilstring endet. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) Gleichheitsvergleich. Mehrere Modi, bereitgestellt durch die StringComparison-Aufzählung, werden unterstützt. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) Gleichheitsvergleich. Verwendet den [System::StringComparison::Ordinal](../stringcomparison/) Vergleichsmodus. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Vergleicht zwei Zeichenfolgen auf Gleichheit unter Verwendung des Ordinal-Vergleichmodus. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Vergleicht zwei Zeichenfolgen auf Gleichheit. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Versucht, ein [String](./) in eine ASCII-Zeichenfolge zu konvertieren. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formatiert die Zeichenfolge im C#-Stil. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formatiert die Zeichenfolge im C#-Stil. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formatiert die Zeichenfolge im C#-Stil. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formatiert die Zeichenfolge im C#-Stil. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formatiert die Zeichenfolge im C#-Stil. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Erstellt [String](./) aus einer ASCII-Zeichenfolge. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Erstellt [String](./) aus einer ASCII-Zeichenfolge. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Erstellt [String](./) aus einer ASCII-Zeichenfolge. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Erstellt [String](./) aus einer UTF-16-Zeichenfolge. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Erstellt [String](./) aus einer UTF-32-Zeichenfolge. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Erstellt [String](./) aus einer UTF-8-Zeichenfolge. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Erstellt [String](./) aus einer UTF-8-Zeichenfolge. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Erstellt [String](./) aus einer UTF-8-Zeichenfolge. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Erstellt [String](./) aus einer UTF-8-Zeichenfolge. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Erstellt [String](./) aus einer Wide-String. |
| int [get_Length](./get_length/)() const | Ermittelt die Länge der Zeichenfolge. |
| int [GetHashCode](./gethashcode/)() const | Erstellt einen Hash der enthaltenen Zeichenfolge. Implementiert in ICU, entspricht nicht den Hashes in C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Vorwärtsnachschlagen eines Teilstrings. |
| int [IndexOf](./indexof/)(char_t, int) const | Vorwärtsnachschlagen eines Zeichens. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Vorwärtsnachschlagen eines Zeichens im Teilstring. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Vorwärtsnachschlagen eines Teilstrings. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Vorwärtsnachschlagen eines Teilstrings. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Vorwärtsnachschlagen eines Teilstrings. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Vorwärtsnachschlagen eines Teilstrings. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Vorwärtsnachschlagen eines Zeichens. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Durchsucht konsequent alle Zeichen von str in dieser Zeichenfolge. Wird das erste Zeichen gefunden, wird seine Position zurückgegeben, andernfalls wird das zweite und so weiter gesucht. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Sucht nach einem der übergebenen Zeichen in der gesamten Zeichenfolge. Vergleicht das erste Zeichen der Zeichenfolge mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten passenden Zeichens zurück. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Sucht nach einem der übergebenen Zeichen im Teilstring. Vergleicht das erste Zeichen des Teilstrings mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten passenden Zeichens zurück. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Sucht nach einem der übergebenen Zeichen im Teilstring. Vergleicht das erste Zeichen des Teilstrings mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten passenden Zeichens zurück. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Fügt einen Teilstring an der angegebenen Position ein. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Prüft, ob das Zeichenfolgenobjekt vom durch [TypeInfo](../typeinfo/) übergebenen Typ ist. |
| **bool** [IsAsciiString](./isasciistring/)() const | Gibt an, ob ein [String](./) nur ASCII-Symbole enthält. |
| **bool** [IsEmpty](./isempty/)() const | Prüft, ob die Zeichenfolge sowohl nicht null als auch leer ist. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Prüft, ob die Unicode-Zeichenfolge mit der angegebenen Normalisierungsform normalisiert ist. |
| **bool** [IsNull](./isnull/)() const | Prüft, ob die Zeichenfolge als null betrachtet wird. [String](./) ist null und nur, wenn sie über den [String()](./string/)-Konstruktor erstellt, verschoben, kopiert oder von einer Null-Zeichenfolge zugewiesen wurde oder die Methode [reset()](./reset/) aufgerufen wurde. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Prüft, ob die Zeichenfolge leer oder als null betrachtet wird. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Prüft, ob die übergebene Zeichenfolge null oder leer ist. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Gibt an, ob eine angegebene Zeichenfolge null, leer oder nur aus Leerzeichen besteht. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Verbindet ein Array unter Verwendung der Zeichenfolge als Trennzeichen. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Verbindet ein Array unter Verwendung der Zeichenfolge als Trennzeichen. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Verbindet ein Array unter Verwendung der Zeichenfolge als Trennzeichen. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Verbindet ein Array unter Verwendung der Zeichenfolge als Trennzeichen. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Rückwärtsnachschlagen eines Teilstrings. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Rückwärtsnachschlagen eines Teilstrings. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Rückwärtsnachschlagen eines Teilstrings. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Rückwärtsnachschlagen eines Teilstrings. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Rückwärtsnachschlagen eines Zeichens. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Rückwärtsnachschlagen eines Zeichens. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Rückwärtsnachschlagen eines Zeichens. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Sucht rückwärts im gesamten String nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen des Strings mit allen Zeichen in anyOf, dann das vorherige usw. Gibt den Index des ersten gefundenen Treffers zurück. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Sucht rückwärts im Teilstring nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen des Teilstrings mit allen Zeichen in anyOf, dann das vorherige usw. Gibt den Index des ersten gefundenen Treffers zurück. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Sucht rückwärts im Teilstring nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen des Teilstrings mit allen Zeichen in anyOf, dann das vorherige usw. Gibt den Index des ersten gefundenen Treffers zurück. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalisiert die Unicode-Zeichenfolge mit der angegebenen Normalisierungsform. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Konvertiert die Zeichenfolge in einen schreibgeschützten Span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Ungleichheits-Vergleichsoperator. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Prüft, ob die Zeichenfolge nicht null ist. Verwendet dieselbe Logik wie der Aufruf von [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) Verkettungsoperator. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) Verkettung mit String-Literal oder Zeichenkettenzeiger. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Fügt der Zeichenfolge ein Zeichen am Ende hinzu. |
| [String](./) [operator+](./operator_plus/)(int) const | Fügt die String-Repräsentation eines ganzzahligen Werts am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Fügt die String-Repräsentation eines vorzeichenlosen Ganzzahlwertes am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Fügt die String-Repräsentation eines Gleitkommawertes am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Fügt die String-Repräsentation eines ganzzahligen Werts am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Fügt die String-Repräsentation eines Referenztyps am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Fügt die String-Repräsentation eines Referenztyps am Ende der Zeichenfolge hinzu. |
| [String](./) [operator+](./operator_plus/)(T) const | Fügt die String-Repräsentation eines booleschen Werts am Ende der Zeichenfolge hinzu. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Verkettungszuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Verkettungszuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Verkettungszuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Verkettungszuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Verkettenzuweisungsoperator. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Verkettenzuweisungsoperator. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Vergleicht Zeichenketten in ihrer Reihenfolge. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Zuweisungsoperator. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Move-Zuweisungsoperator. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Gleichheitsvergleichsoperator. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Überprüft, ob die Zeichenkette null ist. Verwendet dieselbe Logik wie der Aufruf von [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Vergleicht Zeichenketten in ihrer Reihenfolge. |
| char_t [operator[]](./operator[]/)(int) const | Liefert das Zeichen an der angegebenen Position. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Fügt Auffüllung links vom ursprünglichen String hinzu. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Fügt Auffüllung rechts vom ursprünglichen String hinzu. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Gibt den Reverse-Iterator auf das letzte Zeichen (falls vorhanden) des tatsächlichen Zeichenkettenpuffers zurück. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extrahiert alles außer dem Teilstring aus der aktuellen Zeichenkette. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Gibt den Reverse-Iterator auf das Zeichen vor dem ersten (falls vorhanden) des tatsächlichen Zeichenkettenpuffers zurück. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Ersetzt alle Vorkommen des Zeichens in der Zeichenkette. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Ersetzt alle Vorkommen des Suchwertes in dieser Zeichenkette. |
| [String](./)\& [reset](./reset/)() | Setzt die Zeichenkette auf null. Entspricht 'string_variable_name = null' in C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Setzt das Zeichen an der angegebenen Position. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Zeichens. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Zeichens. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines von zwei Zeichen. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines der angegebenen Zeichen. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines der angegebenen Zeichen. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Teilstrings. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Teilstrings. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Teilstrings. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Teilt die Zeichenkette anhand eines Teilstrings. Derzeit werden Trennzeichen-Arrays mit null oder einem Element unterstützt. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring beginnt. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring beginnt. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring beginnt. |
|  [String](./string/)() | Standardkonstruktor. Erstellt ein Zeichenkettenobjekt, das als null angesehen wird. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem String-Literal. Betrachtet das Literal als nullterminierten String und berechnet die Ziel-Länge basierend auf der Literalgröße. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem Zeiger auf eine Zeichenkette. Behandelt den referenzierten String als nullterminiert und berechnet die Ziel-Länge anhand des Nullzeichens. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem String-Literal. Betrachtet das Literal als nullterminierten UTF-8-String und berechnet die Ziel-Länge basierend auf der Literalgröße. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem Zeiger auf eine Zeichenkette. Behandelt den referenzierten String als nullterminierten UTF-8-String und berechnet die Ziel-Länge anhand des Nullzeichens. |
| [String](./string/)(const char16_t *, int) | Erzeugt eine Zeichenkette aus einem Zeiger auf eine Zeichenkette und einer expliziten Länge. |
| [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Initialisiert eine neue Instanz der [System.String](./) Klasse mit den Unicode-Zeichen, die im angegebenen schreibgeschützten Span angegeben sind. |
| [String](./string/)(const char *, int) | Erzeugt eine Zeichenkette aus einem Zeiger auf eine Zeichenkette und einer expliziten Länge. |
| [String](./string/)(const char16_t *, int, int) | Erzeugt eine Zeichenkette aus einem Zeiger auf eine Zeichenkette, beginnend an einer Position, unter Verwendung einer Länge. |
| explicit  [String](./string/)(const char16_t, int) | Füllkonstruktor. |
| [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Nullptr-Konstruktor. Als Template deklariert, um Prioritäten mit anderen Template-Konstruktoren zu lösen. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem Wide-String-Literal. Betrachtet das Literal als nullterminierten String und berechnet die Ziel-Länge basierend auf der Literalgröße. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Erzeugt eine Zeichenkette basierend auf einem Zeiger auf einen Wide-Character-String. Behandelt den referenzierten String als nullterminiert und berechnet die Ziel-Länge anhand des Nullzeichens. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Erzeugt eine Zeichenkette aus einem Zeiger auf einen Wide-Character-String und einer expliziten Länge. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt. |
| explicit  [String](./string/)(const **wchar_t**, int) | Füllkonstruktor. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitaufwendig, daher sind implizite Konvertierungen nicht erlaubt. |
| [String](./string/)(const [String](./)\&) | Kopie-Konstruktor. |
| [String](./string/)([String](./)\&&) | Move-Konstruktor. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Konvertiert das gesamte Zeichenarray in eine Zeichenkette. |
| [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Konvertiert einen Teilbereich eines Zeichenarrays in eine Zeichenkette. Wenn Parameter außerhalb des Array-Bereichs liegen, wird eine leere Zeichenkette erstellt. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Wickelt UnicodeString in [String](./) ein. |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Move-Konstruktor. |
| explicit  [String](./string/)(const std::wstring\&) | Erstellt [String](./) aus einem Wide-String. |
| explicit  [String](./string/)(const std::u16string\&) | Erstellt [String](./) aus einem UTF-16-String. |
| explicit  [String](./string/)(const std::string\&) | Erstellt [String](./) aus einem std::string, das im UTF-8-Format vorliegt. |
| explicit  [String](./string/)(const std::u32string\&) | Erstellt [String](./) aus einem std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extrahiert Teilstring. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extrahiert Teilstring. |
| std::string [ToAsciiString](./toasciistring/)() const | Konvertiert die Zeichenkette zu std::string. Verwendet ASCII-Codierung. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Konvertiert die Zeichenkette oder den Teilstring zu einem Byte-Array. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Konvertiert die Zeichenkette oder den Teilstring zu einem Zeichen-Array. |
| [String](./) [ToLower](./tolower/)() const | Konvertiert alle Zeichen der Zeichenkette zu Kleinbuchstaben. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konvertiert alle Zeichen der Zeichenkette zu Kleinbuchstaben unter Verwendung einer spezifischen Kultur. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Konvertiert alle Zeichen der Zeichenkette zu Kleinbuchstaben unter Verwendung einer invarianten Kultur. |
| [String](./) [ToString](./tostring/)() const | Wrapper zur Handhabung der [String](./) Klasse in Kontexten, in denen [ToString()](./tostring/) für Objekte von Werttypen aufgerufen wird. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper zur Handhabung der [String](./) Klasse in Kontexten, in denen [ToString()](./tostring/) für Objekte von Werttypen aufgerufen wird. |
| std::u16string [ToU16Str](./tou16str/)() const | Konvertiert die Zeichenkette zu std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Konvertiert die Zeichenkette zu std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Konvertiert alle Zeichen der Zeichenkette zu Großbuchstaben. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Konvertiert alle Zeichen der Zeichenkette zu Großbuchstaben unter Verwendung einer spezifischen Kultur. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Konvertiert alle Zeichen der Zeichenkette zu Großbuchstaben unter Verwendung einer invarianten Kultur. |
| std::string [ToUtf8String](./toutf8string/)() const | Konvertiert die Zeichenkette zu std::string. Verwendet UTF-8-Codierung. |
| std::wstring [ToWCS](./towcs/)() const | Konvertiert die Zeichenkette zu std::wstring. |
| [String](./) [Trim](./trim/)() const | Entfernt alle Leerzeichen von sowohl Anfang als auch Ende der Zeichenkette. |
| [String](./) [Trim](./trim/)(char_t) const | Entfernt alle Vorkommen des übergebenen Zeichens von sowohl Anfang als auch Ende der Zeichenkette. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Entfernt alle Vorkommen der übergebenen Zeichen von sowohl Anfang als auch Ende der Zeichenkette. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Entfernt alle Vorkommen der übergebenen Zeichen von sowohl Anfang als auch Ende der Zeichenkette. |
| [String](./) [TrimEnd](./trimend/)() const | Entfernt alle Leerzeichen vom Ende der Zeichenkette. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Entfernt alle Vorkommen des übergebenen Zeichens vom Ende der Zeichenkette. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Entfernt alle Vorkommen der übergebenen Zeichen vom Ende der Zeichenkette. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Entfernt alle Vorkommen der übergebenen Zeichen vom Ende der Zeichenkette. |
| [String](./) [TrimStart](./trimstart/)() const | Entfernt alle Leerzeichen vom Anfang der Zeichenkette. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Entfernt alle Vorkommen des übergebenen Zeichens vom Anfang der Zeichenkette. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Entfernt alle Vorkommen der übergebenen Zeichen vom Anfang der Zeichenkette. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Entfernt alle Vorkommen der übergebenen Zeichen vom Anfang der Zeichenkette. |
| const UChar * [u_str](./u_str/)() const | Gibt einen nullterminierten Puffer im ICU-Stil zurück. Kann die Zeichenkette neu allokieren. |
| [~String](./~string/)() | Destruktor. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Leere Zeichenkette. |
| static [Null](./null/) | Null-Zeichenkette. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Reverse-Iterator-Typ. |
## Bemerkungen



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Erstelle einen String aus dem Zeichenarray und gib ihn aus.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Erstelle einen String aus dem Byte-Array und gib ihn aus.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Trimme den String unten und gib ihn aus.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Gib die Anzahl der Wörter im String aus.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)