---
title: Char
second_title: Aspose.Slides dla C++ – odniesienie API
description: Udostępnia metody służące do manipulacji znakami reprezentowanymi jako jednostki kodu UTF-16. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 170
url: /pl/system/char/
---
## Klasa Char


Udostępnia metody służące do manipulacji znakami reprezentowanymi jako jednostki kodu UTF-16. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Char
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Konwertuje jednostkę kodu UTF-32 na instancję klasy [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Konwertuje określoną parę zastępczą UTF-16 na jednostkę kodu UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Konwertuje wartość znaku zakodowanego w UTF-16 lub pary zastępczej w określonym położeniu w ciągu znaków na jednostkę kodu UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Konwertuje określony znak UTF-16 na wartość liczbową zmiennoprzecinkową podwójnej precyzji. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Zwraca wartość, która reprezentuje kategorię Unicode określonego znaku. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Określa, czy określony znak jest klasyfikowany jako biały znak ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako znak kontrolny Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Określa, czy określony znak jest klasyfikowany jako znak kontrolny Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako cyfra dziesiętna. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Określa, czy znak pod określonym indeksem w podanym ciągu jest klasyfikowany jako cyfra dziesiętna. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Określa, czy określony znak jest klasyfikowany jako cyfra dziesiętna. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Określa, czy znak pod określonym indeksem w podanym ciągu jest jednostką high surrogate UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest high surrogate. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Określa, czy określony znak jest high surrogate. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako litera Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Określa, czy określony znak jest klasyfikowany jako litera Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako litera Unicode lub cyfra dziesiętna. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Określa, czy określony znak jest klasyfikowany jako litera Unicode lub cyfra dziesiętna. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako mała litera. |
| static **bool** [IsLower](./islower/)(char_t) | Określa, czy określony znak jest klasyfikowany jako mała litera. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Określa, czy znak pod określonym indeksem w podanym ciągu jest klasyfikowany jako mała litera. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest low surrogate. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Określa, czy określony znak jest low surrogate. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako liczba. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Określa, czy określony znak jest klasyfikowany jako liczba. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako znak interpunkcyjny. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Określa, czy określony znak jest klasyfikowany jako znak interpunkcyjny. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako znak separatora. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Określa, czy określony znak jest klasyfikowany jako znak separatora. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Określa, czy określony znak jest jednostką kodu surrogatu UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Określa, czy znak pod określonym indeksem w podanym ciągu jest jednostką kodu surrogatu UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Określa, czy dwa określone znaki tworzą parę zastępczą UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Określa, czy dwa kolejne znaki w podanym buforze znaków są parą zastępczą. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako znak symbolu. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Określa, czy określony znak jest klasyfikowany jako znak symbolu. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Określa, czy znak pod określonym indeksem w podanym ciągu jest klasyfikowany jako wielka litera. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako wielka litera. |
| static **bool** [IsUpper](./isupper/)(char_t) | Określa, czy określony znak jest klasyfikowany jako wielka litera. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Określa, czy znak pod określonym indeksem w podanym buforze znaków jest klasyfikowany jako znak białej spacji. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Określa, czy określony znak jest klasyfikowany jako znak białej spacji. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Określa, czy znak pod określonym indeksem w podanym ciągu jest klasyfikowany jako znak białej spacji. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Konwertuje pierwszy i jedyny znak podanego ciągu na wartość char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Konwertuje określony znak na małą literę. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konwertuje określony znak na małą literę. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Konwertuje określony znak na małą literę. |
| static char_t [ToUpper](./toupper/)(char_t) | Konwertuje określony znak na wielką literę. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konwertuje określony znak na wielką literę. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Konwertuje określony znak na wielką literę. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Próbuje przekonwertować ciąg składający się z jednego znaku na znak UTF-16. Funkcja zakończy się sukcesem tylko wtedy, gdy ciąg wejściowy nie jest nullem i ma długość dokładnie jednego znaku. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)