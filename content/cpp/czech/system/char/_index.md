---
title: Char
second_title: Aspose.Slides pro C++ referenci API
description: Poskytuje metody pro manipulaci se znaky reprezentovanými jako jednotky kódu UTF-16. Jedná se o statický typ bez služeb instance. Neměli byste jej nikdy vytvářet jako instanci jakýmkoli způsobem.
type: docs
weight: 170
url: /cs/system/char/
---
## Třída Char

Poskytuje metody pro manipulaci se znaky reprezentovanými jako jednotky kódu UTF-16. Jedná se o statický typ bez služeb instance. Neměli byste jej nikdy vytvářet jako instanci jakýmkoli způsobem.

```cpp
class Char
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Převádí kódovou jednotku UTF-32 na instanci třídy [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Převádí zadaný pár náhradní znaky UTF-16 na kódovou jednotku UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Převádí hodnotu znaku kódovaného v UTF-16 nebo páru náhradních znaků na určené pozici v řetězci na kódovou jednotku UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Převádí zadaný znak UTF-16 na číselnou hodnotu s dvojitou přesností. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Vrací hodnotu, která představuje kategorii Unicode zadaného znaku. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Určuje, zda je zadaný znak klasifikován jako ASCII bílý znak. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako řídící znak Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Určuje, zda je zadaný znak klasifikován jako řídící znak Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako desetinná číslice. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci klasifikován jako desetinná číslice. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Určuje, zda je zadaný znak klasifikován jako desetinná číslice. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci vysoký náhradní kód UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků vysoký náhradní znak. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Určuje, zda je zadaný znak vysoký náhradní znak. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako písmeno Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Určuje, zda je zadaný znak klasifikován jako písmeno Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako písmeno Unicode nebo desetinná číslice. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Určuje, zda je zadaný znak klasifikován jako písmeno Unicode nebo desetinná číslice. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako malé písmeno. |
| static **bool** [IsLower](./islower/)(char_t) | Určuje, zda je zadaný znak klasifikován jako malé písmeno. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci klasifikován jako malé písmeno. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků nízký náhradní znak. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Určuje, zda je zadaný znak nízký náhradní znak. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako číslo. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Určuje, zda je zadaný znak klasifikován jako číslo. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako interpunkční znak. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Určuje, zda je zadaný znak klasifikován jako interpunkční znak. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako oddělovač. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Určuje, zda je zadaný znak klasifikován jako oddělovač. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Určuje, zda je zadaný znak kódovou jednotkou náhradního znaku UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci kódovou jednotkou náhradního znaku UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Určuje, zda jsou dva zadané znaky párem náhradních znaků UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Určuje, zda dva po sobě jdoucí znaky ve specifikovaném bufferu znaků tvoří náhradní pár. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako symbol. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Určuje, zda je zadaný znak klasifikován jako symbol. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci klasifikován jako velké písmeno. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako velké písmeno. |
| static **bool** [IsUpper](./isupper/)(char_t) | Určuje, zda je zadaný znak klasifikován jako velké písmeno. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném bufferu znaků klasifikován jako bílý znak. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Určuje, zda je zadaný znak klasifikován jako bílý znak. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Určuje, zda je znak na zadaném indexu ve specifikovaném řetězci klasifikován jako bílý znak. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Převádí první a jediný znak zadaného řetězce na hodnotu typu char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Převádí zadaný znak na malé písmeno. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Převádí zadaný znak na malé písmeno. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Převádí zadaný znak na malé písmeno. |
| static char_t [ToUpper](./toupper/)(char_t) | Převádí zadaný znak na velké písmeno. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Převádí zadaný znak na velké písmeno. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Převádí zadaný znak na velké písmeno. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Pokouší se převést řetězec obsahující jediný znak na znak UTF-16. Funkce uspěje pouze pokud vstupní řetězec není null a má délku přesně jednoho znaku. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)