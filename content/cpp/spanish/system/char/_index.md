---
title: Char
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona métodos para la manipulación de caracteres representados como unidades de código UTF-16. Este es un tipo estático sin servicios de instancia. No debe crear instancias de él por ningún medio.
type: docs
weight: 170
url: /es/system/char/
---
## Clase Char

Proporciona métodos para la manipulación de caracteres representados como unidades de código UTF-16. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Char
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Convierte una unidad de código UTF-32 en una instancia de la clase [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Convierte el par sustituto UTF-16 especificado en una unidad de código UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Convierte el valor de un carácter codificado en UTF-16 o un par sustituto en una posición especificada dentro de una cadena en una unidad de código UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Convierte el carácter UTF-16 especificado en un valor numérico de punto flotante de doble precisión. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Devuelve un valor que representa la categoría Unicode del carácter especificado. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de espacio en blanco ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de control Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de control Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un dígito decimal. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como un dígito decimal. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Determina si el carácter especificado está clasificado como un dígito decimal. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código sustituto alto UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado es un sustituto alto. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Determina si el carácter especificado es un sustituto alto. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Determina si el carácter especificado está clasificado como una letra Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra Unicode o un dígito decimal. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Determina si el carácter especificado está clasificado como una letra Unicode o un dígito decimal. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra minúscula. |
| static **bool** [IsLower](./islower/)(char_t) | Determina si el carácter especificado está clasificado como una letra minúscula. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como una letra minúscula. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado es un sustituto bajo. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Determina si el carácter especificado es un sustituto bajo. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un número. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Determina si el carácter especificado está clasificado como un número. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de puntuación. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de puntuación. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter separador. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Determina si el carácter especificado está clasificado como un carácter separador. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Determina si el carácter especificado es una unidad de código sustituto UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Determina si el carácter en el índice especificado de la cadena especificada es una unidad de código sustituto UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Determina si los dos caracteres especificados forman un par sustituto UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Determina si dos caracteres consecutivos en el búfer de caracteres especificado forman un par sustituto. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de símbolo. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de símbolo. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como una letra mayúscula. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como una letra mayúscula. |
| static **bool** [IsUpper](./isupper/)(char_t) | Determina si el carácter especificado está clasificado como una letra mayúscula. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Determina si el carácter en el índice especificado del búfer de caracteres especificado está clasificado como un carácter de espacio en blanco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Determina si el carácter especificado está clasificado como un carácter de espacio en blanco. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Determina si el carácter en el índice especificado de la cadena especificada está clasificado como un carácter de espacio en blanco. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Convierte el primer y único carácter de la cadena especificada a un valor char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Convierte el carácter especificado a minúsculas. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convierte el carácter especificado a minúsculas. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Convierte el carácter especificado a minúsculas. |
| static char_t [ToUpper](./toupper/)(char_t) | Convierte el carácter especificado a mayúsculas. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convierte el carácter especificado a mayúsculas. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Convierte el carácter especificado a mayúsculas. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Intenta convertir una cadena que consta de un solo carácter en un carácter UTF-16. La función solo tiene éxito cuando la cadena de entrada no es nula y tiene una longitud de exactamente un carácter. |

## Ver también

* Namespace [System](../)
* Library [Aspose.Slides](../../)