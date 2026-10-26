---
title: Char
second_title: Referência da API Aspose.Slides para C++
description: Fornece métodos para manipulação de caracteres representados como unidades de código UTF-16. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por nenhum meio.
type: docs
weight: 170
url: /pt/system/char/
---
## Classe Char

Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Converte unidade de código UTF-32 em uma instância da classe [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Converte o par substituto UTF-16 especificado em unidade de código UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Converte o valor de um caractere codificado em UTF-16 ou de um par substituto em uma posição especificada em uma string para unidade de código UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Converte o caractere UTF-16 especificado em valor numérico de ponto flutuante de precisão dupla. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Retorna um valor que representa a categoria Unicode do caractere especificado. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determina se o caractere especificado é classificado como um caractere de espaço em branco ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um caractere de controle Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Determina se o caractere especificado é classificado como um caractere de controle Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um dígito decimal. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Determina se o caractere no índice especificado na string especificada é classificado como um dígito decimal. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Determina se o caractere especificado é classificado como um dígito decimal. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Determina se o caractere no índice especificado na string especificada é uma unidade de código substituto alto UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é um substituto alto. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determina se o caractere especificado é um substituto alto. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como uma letra Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Determina se o caractere especificado é classificado como uma letra Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como uma letra Unicode ou um dígito decimal. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Determina se o caractere especificado é classificado como uma letra Unicode ou um dígito decimal. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como uma letra minúscula. |
| static **bool** [IsLower](./islower/)(char_t) | Determina se o caractere especificado é classificado como uma letra minúscula. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Determina se o caractere no índice especificado na string especificada é classificado como uma letra minúscula. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é um substituto baixo. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Determina se o caractere especificado é um substituto baixo. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um número. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Determina se o caractere especificado é classificado como um número. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um caractere de pontuação. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Determina se o caractere especificado é classificado como um caractere de pontuação. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um caractere separador. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Determina se o caractere especificado é classificado como um caractere separador. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Determina se o caractere especificado é uma unidade de código substituto UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Determina se o caractere no índice especificado na string especificada é uma unidade de código substituto UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determina se os dois caracteres especificados formam um par substituto UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Determina se dois caracteres consecutivos no buffer de caracteres especificado são um par substituto. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um caractere símbolo. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Determina se o caractere especificado é classificado como um caractere símbolo. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Determina se o caractere no índice especificado na string especificada é classificado como uma letra maiúscula. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como uma letra maiúscula. |
| static **bool** [IsUpper](./isupper/)(char_t) | Determina se o caractere especificado é classificado como uma letra maiúscula. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determina se o caractere no índice especificado no buffer de caracteres especificado é classificado como um caractere de espaço em branco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Determina se o caractere especificado é classificado como um caractere de espaço em branco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Determina se o caractere no índice especificado na string especificada é classificado como um caractere de espaço em branco. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Converte o primeiro e único caractere da string especificada para um valor char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Converte o caractere especificado para minúsculas. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte o caractere especificado para minúsculas. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Converte o caractere especificado para minúsculas. |
| static char_t [ToUpper](./toupper/)(char_t) | Converte o caractere especificado para maiúsculas. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converte o caractere especificado para maiúsculas. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Converte o caractere especificado para maiúsculas. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Tenta converter uma string contendo um único caractere em um caractere UTF-16. A função tem sucesso somente quando a string de entrada não é nula e tem comprimento exatamente de um caractere. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)