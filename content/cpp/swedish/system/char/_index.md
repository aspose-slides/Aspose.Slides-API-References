---
title: Char
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoder för manipulering av tecken som representeras som UTF-16-kodenheter. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 170
url: /sv/system/char/
---
## Char-klass

Tillhandahåller metoder för manipulering av tecken som representeras som UTF-16 kodenheter. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Char
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Konverterar UTF-32-kodenhet till en instans av klassen [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Konverterar det angivna UTF-16-surrogatparet till en UTF-32-kodenhet. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Konverterar värdet av ett UTF-16-kodat tecken eller surrogatpar på en specificerad position i en sträng till en UTF-32-kodenhet. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Konverterar det angivna UTF-16-tecknet till ett dubbelprecisionsflyttal. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Returnerar ett värde som representerar en Unicode-kategori för det angivna tecknet. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Avgör om det angivna tecknet klassificeras som ett ASCII-mellanslagstecken. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett Unicode-kontrolltecken. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Avgör om det angivna tecknet klassificeras som ett Unicode-kontrolltecken. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som en decimalsiffra. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Avgör om tecknet på den angivna indexen i den angivna strängen klassificeras som en decimalsiffra. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Avgör om det angivna tecknet klassificeras som en decimalsiffra. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Avgör om tecknet på den angivna indexen i den angivna strängen är en hög surrogat-kodenhet i UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten är ett högt surrogat. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Avgör om det angivna tecknet är ett högt surrogat. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som en Unicode-bokstav. |
| static **bool** [IsLetter](./isletter/)(char_t) | Avgör om det angivna tecknet klassificeras som en Unicode-bokstav. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som en Unicode-bokstav eller en decimalsiffra. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Avgör om det angivna tecknet klassificeras som en Unicode-bokstav eller en decimalsiffra. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som en gemen bokstav. |
| static **bool** [IsLower](./islower/)(char_t) | Avgör om det angivna tecknet klassificeras som en gemen bokstav. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Avgör om tecknet på den angivna indexen i den angivna strängen klassificeras som en gemen bokstav. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten är ett lågt surrogat. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Avgör om det angivna tecknet är ett lågt surrogat. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett tal. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Avgör om det angivna tecknet klassificeras som ett tal. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett skiljetecken. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Avgör om det angivna tecknet klassificeras som ett skiljetecken. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett separator-tecken. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Avgör om det angivna tecknet klassificeras som ett separator-tecken. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Avgör om det angivna tecknet är en UTF-16-surrogat-kodenhet. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Avgör om tecknet på den angivna indexen i den angivna strängen är en UTF-16-surrogat-kodenhet. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Avgör om de två angivna tecknen utgör ett UTF-16-surrogatpar. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Avgör om två på varandra följande tecken i den angivna teckenbufferten bildar ett surrogatpar. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett symboltecken. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Avgör om det angivna tecknet klassificeras som ett symboltecken. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Avgör om tecknet på den angivna indexen i den angivna strängen klassificeras som en versal bokstav. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som en versal bokstav. |
| static **bool** [IsUpper](./isupper/)(char_t) | Avgör om det angivna tecknet klassificeras som en versal bokstav. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Avgör om tecknet på den angivna indexen i den angivna teckenbufferten klassificeras som ett mellanslagstecken. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Avgör om det angivna tecknet klassificeras som ett mellanslagstecken. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Avgör om tecknet på den angivna indexen i den angivna strängen klassificeras som ett mellanslagstecken. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Konverterar det första och enda tecknet i den angivna strängen till ett char_t-värde. |
| static char_t [ToLower](./tolower/)(char_t) | Konverterar det angivna tecknet till gemener. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konverterar det angivna tecknet till gemener. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Konverterar det angivna tecknet till gemener. |
| static char_t [ToUpper](./toupper/)(char_t) | Konverterar det angivna tecknet till versaler. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konverterar det angivna tecknet till versaler. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Konverterar det angivna tecknet till versaler. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Försöker konvertera en sträng bestående av ett enda tecken till ett UTF-16-tecken. Funktionen lyckas endast när inmatningssträngen inte är null och har exakt en teckenlängd. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)