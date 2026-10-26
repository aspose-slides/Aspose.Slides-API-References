---
title: Char
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Methoden zur Manipulation von Zeichen bereit, die als UTF-16-Codeeinheiten dargestellt werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 170
url: /de/system/char/
---
## Char-Klasse

Stellt Methoden zur Manipulation von Zeichen bereit, die als UTF-16-Codeeinheiten dargestellt werden. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Char
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Konvertiert eine UTF-32-Codeeinheit in eine Instanz der [System::String](../string/) Klasse. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Konvertiert das angegebene UTF-16-Surrogatpaar in eine UTF-32-Codeeinheit. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Konvertiert den Wert eines UTF-16-codierten Zeichens oder Surrogatpaars an einer angegebenen Position in einem String in eine UTF-32-Codeeinheit. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Konvertiert das angegebene UTF-16-Zeichen in einen double-genauen Fließkommawert. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Gibt einen Wert zurück, der die Unicode-Kategorie des angegebenen Zeichens darstellt. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Bestimmt, ob das angegebene Zeichen als ASCII-Leerstelle klassifiziert ist. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Steuerzeichen klassifiziert ist. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Steuerzeichen klassifiziert ist. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als dezimale Ziffer klassifiziert ist. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String als dezimale Ziffer klassifiziert ist. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Bestimmt, ob das angegebene Zeichen als dezimale Ziffer klassifiziert ist. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String eine UTF-16-High-Surrogat-Codeeinheit ist. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer ein High-Surrogat ist. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen ein High-Surrogat ist. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Buchstabe klassifiziert ist. |
| static **bool** [IsLetter](./isletter/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Buchstabe klassifiziert ist. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Unicode-Buchstabe oder dezimale Ziffer klassifiziert ist. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Bestimmt, ob das angegebene Zeichen als Unicode-Buchstabe oder dezimale Ziffer klassifiziert ist. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Kleinbuchstabe klassifiziert ist. |
| static **bool** [IsLower](./islower/)(char_t) | Bestimmt, ob das angegebene Zeichen als Kleinbuchstabe klassifiziert ist. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String als Kleinbuchstabe klassifiziert ist. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer ein Low-Surrogat ist. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen ein Low-Surrogat ist. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Zahl klassifiziert ist. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Bestimmt, ob das angegebene Zeichen als Zahl klassifiziert ist. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Satzzeichen klassifiziert ist. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Bestimmt, ob das angegebene Zeichen als Satzzeichen klassifiziert ist. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Trennzeichen klassifiziert ist. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Bestimmt, ob das angegebene Zeichen als Trennzeichen klassifiziert ist. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Bestimmt, ob das angegebene Zeichen eine UTF-16-Surrogat-Codeeinheit ist. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String eine UTF-16-Surrogat-Codeeinheit ist. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Bestimmt, ob die beiden angegebenen Zeichen ein UTF-16-Surrogatpaar bilden. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Bestimmt, ob zwei aufeinanderfolgende Zeichen im angegebenen Zeichenpuffer ein Surrogatpaar bilden. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Symbol klassifiziert ist. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Bestimmt, ob das angegebene Zeichen als Symbol klassifiziert ist. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String als Großbuchstabe klassifiziert ist. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Großbuchstabe klassifiziert ist. |
| static **bool** [IsUpper](./isupper/)(char_t) | Bestimmt, ob das angegebene Zeichen als Großbuchstabe klassifiziert ist. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen Zeichenpuffer als Leerzeichen klassifiziert ist. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Bestimmt, ob das angegebene Zeichen als Leerzeichen klassifiziert ist. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Bestimmt, ob das Zeichen am angegebenen Index im angegebenen String als Leerzeichen klassifiziert ist. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Konvertiert das erste und einzige Zeichen des angegebenen Strings in einen char_t-Wert. |
| static char_t [ToLower](./tolower/)(char_t) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Konvertiert das angegebene Zeichen in Kleinbuchstaben. |
| static char_t [ToUpper](./toupper/)(char_t) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Konvertiert das angegebene Zeichen in Großbuchstaben. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Versucht, einen String, der aus einem einzelnen Zeichen besteht, in ein UTF-16-Zeichen zu konvertieren. Die Funktion ist nur erfolgreich, wenn der Eingabestring nicht null ist und genau ein Zeichen lang ist. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)