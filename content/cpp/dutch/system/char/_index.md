---
title: Char
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt methoden voor het manipuleren van tekens die worden weergegeven als UTF-16 code-eenheden. Dit is een statisch type zonder instantie-services. Je mag onder geen enkele omstandigheid instanties ervan maken.
type: docs
weight: 170
url: /nl/system/char/
---
## Char-klasse

Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Methoden

| Method | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Converteert een UTF-32-code-eenheid naar een instantie van de [System::String](../string/)-klasse. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Converteert het opgegeven UTF-16-surrogaatpaar naar een UTF-32-code-eenheid. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Converteert de waarde van een UTF-16-gecodeerd teken of surrogaatpaar op een opgegeven positie in een tekenreeks naar een UTF-32-code-eenheid. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Converteert het opgegeven UTF-16-teken naar een double-precisie floating-point numerieke waarde. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Retourneert een waarde die de Unicode-categorie van het opgegeven teken weergeeft. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een ASCII whitespace-teken. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een Unicode-controleteken. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een Unicode-controleteken. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een decimaal cijfer. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks geclassificeerd is als een decimaal cijfer. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een decimaal cijfer. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks een UTF-16 high surrogate-code-eenheid is. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer een high surrogate is. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Bepaalt of het opgegeven teken een high surrogate is. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een Unicode-letter. |
| static **bool** [IsLetter](./isletter/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een Unicode-letter. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een Unicode-letter of een decimaal cijfer. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een Unicode-letter of een decimaal cijfer. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een kleine letter. |
| static **bool** [IsLower](./islower/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een kleine letter. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks geclassificeerd is als een kleine letter. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer een low surrogate is. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Bepaalt of het opgegeven teken een low surrogate is. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een getal. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een getal. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een leesteken. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een leesteken. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een scheidingsteken. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een scheidingsteken. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Bepaalt of het opgegeven teken een UTF-16 surrogaatcode-eenheid is. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks een UTF-16 surrogaatcode-eenheid is. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Bepaalt of de twee opgegeven tekens een geldig UTF-16 surrogaatpaar vormen. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Bepaalt of twee opeenvolgende tekens in de opgegeven tekenbuffer een surrogaatpaar vormen. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een symboolteken. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een symboolteken. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks geclassificeerd is als een hoofdletter. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een hoofdletter. |
| static **bool** [IsUpper](./isupper/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een hoofdletter. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenbuffer geclassificeerd is als een witruimte-teken. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Bepaalt of het opgegeven teken geclassificeerd is als een witruimte-teken. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Bepaalt of het teken op de opgegeven index in de opgegeven tekenreeks geclassificeerd is als een witruimte-teken. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Converteert het eerste en enige teken van de opgegeven tekenreeks naar een char_t-waarde. |
| static char_t [ToLower](./tolower/)(char_t) | Converteert het opgegeven teken naar kleine letters. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converteert het opgegeven teken naar kleine letters. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Converteert het opgegeven teken naar kleine letters. |
| static char_t [ToUpper](./toupper/)(char_t) | Converteert het opgegeven teken naar hoofdletters. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converteert het opgegeven teken naar hoofdletters. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Converteert het opgegeven teken naar hoofdletters. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Probeert een tekenreeks die uit één teken bestaat te converteren naar een UTF-16-teken. De functie slaagt alleen wanneer de invoertekenreeks niet null is en precies één teken lang is. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)