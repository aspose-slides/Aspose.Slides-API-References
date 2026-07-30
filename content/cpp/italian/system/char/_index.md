---
title: Char
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi per la manipolazione dei caratteri rappresentati come unità di codice UTF-16. È un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 170
url: /it/system/char/
---
## Classe Char


Fornisce metodi per la manipolazione dei caratteri rappresentati come unità di codice UTF-16. È un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Char
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Converte l'unità di codice UTF-32 in un'istanza della classe [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Converte la coppia surrogata UTF-16 specificata in un'unità di codice UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Converte il valore di un carattere codificato UTF-16 o di una coppia surrogata nella posizione specificata in una stringa in un'unità di codice UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Converte il carattere UTF-16 specificato in un valore numerico a doppia precisione. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Restituisce un valore che rappresenta la categoria Unicode del carattere specificato. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determina se il carattere specificato è classificato come carattere di spazio bianco ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come carattere di controllo Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Determina se il carattere specificato è classificato come carattere di controllo Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come cifra decimale. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Determina se il carattere all'indice specificato nella stringa specificata è classificato come cifra decimale. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Determina se il carattere specificato è classificato come cifra decimale. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Determina se il carattere all'indice specificato nella stringa specificata è un'unità di codice surrogata alta UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è una surrogata alta. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determina se il carattere specificato è una surrogata alta. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come lettera Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Determina se il carattere specificato è classificato come lettera Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come lettera Unicode o cifra decimale. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Determina se il carattere specificato è classificato come lettera Unicode o cifra decimale. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come lettera minuscola. |
| static **bool** [IsLower](./islower/)(char_t) | Determina se il carattere specificato è classificato come lettera minuscola. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Determina se il carattere all'indice specificato nella stringa specificata è classificato come lettera minuscola. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è una surrogata bassa. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Determina se il carattere specificato è una surrogata bassa. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come numero. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Determina se il carattere specificato è classificato come numero. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come carattere di punteggiatura. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Determina se il carattere specificato è classificato come carattere di punteggiatura. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come carattere separatore. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Determina se il carattere specificato è classificato come carattere separatore. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Determina se il carattere specificato è un'unità di codice surrogata UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Determina se il carattere all'indice specificato nella stringa specificata è un'unità di codice surrogata UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determina se i due caratteri specificati formano una coppia surrogata UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Determina se due caratteri consecutivi nel buffer di caratteri specificato formano una coppia surrogata. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come carattere simbolo. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Determina se il carattere specificato è classificato come carattere simbolo. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Determina se il carattere all'indice specificato nella stringa specificata è classificato come lettera maiuscola. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come lettera maiuscola. |
| static **bool** [IsUpper](./isupper/)(char_t) | Determina se il carattere specificato è classificato come lettera maiuscola. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determina se il carattere all'indice specificato nel buffer di caratteri specificato è classificato come carattere di spazio bianco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Determina se il carattere specificato è classificato come carattere di spazio bianco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Determina se il carattere all'indice specificato nella stringa specificata è classificato come carattere di spazio bianco. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Converte il primo e unico carattere della stringa specificata in un valore char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Converte il carattere specificato in minuscolo. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte il carattere specificato in minuscolo. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Converte il carattere specificato in minuscolo. |
| static char_t [ToUpper](./toupper/)(char_t) | Converte il carattere specificato in maiuscolo. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte il carattere specificato in maiuscolo. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Converte il carattere specificato in maiuscolo. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Tenta di convertire una stringa composta da un singolo carattere in un carattere UTF-16. La funzione ha successo solo quando la stringa di input non è nulla e ha lunghezza esattamente di un carattere. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)