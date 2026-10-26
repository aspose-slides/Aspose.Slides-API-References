---
title: Char
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des méthodes pour la manipulation de caractères représentés sous forme d'unités de code UTF-16. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type, quel que soit le moyen.
type: docs
weight: 170
url: /fr/system/char/
---
## Char classe

Provides methods for manipulation of characters represented as UTF-16 code units. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Char
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Convertit l'unité de code UTF-32 en une instance de la classe [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Convertit la paire de substituts UTF-16 spécifiée en unité de code UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Convertit la valeur d'un caractère ou d'une paire de substituts encodés en UTF-16 à une position spécifiée dans une chaîne en unité de code UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Convertit le caractère UTF-16 spécifié en une valeur numérique à virgule flottante double précision. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Renvoie une valeur qui représente la catégorie Unicode du caractère spécifié. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère d'espace blanc ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un caractère de contrôle Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère de contrôle Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un chiffre décimal. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est classé comme un chiffre décimal. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Détermine si le caractère spécifié est classé comme un chiffre décimal. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est une unité de code haut substitut UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est un haut substitut. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Détermine si le caractère spécifié est un haut substitut. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme une lettre Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Détermine si le caractère spécifié est classé comme une lettre Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme une lettre Unicode ou un chiffre décimal. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Détermine si le caractère spécifié est classé comme une lettre Unicode ou un chiffre décimal. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme une lettre minuscule. |
| static **bool** [IsLower](./islower/)(char_t) | Détermine si le caractère spécifié est classé comme une lettre minuscule. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est classé comme une lettre minuscule. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est un bas substitut. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Détermine si le caractère spécifié est un bas substitut. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un nombre. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Détermine si le caractère spécifié est classé comme un nombre. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un caractère de ponctuation. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère de ponctuation. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un caractère séparateur. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère séparateur. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Détermine si le caractère spécifié est une unité de code substitut UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est une unité de code substitut UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Détermine si les deux caractères spécifiés forment une paire de substituts UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Détermine si deux caractères consécutifs dans le tampon de caractères spécifié forment une paire de substituts. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un caractère symbole. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère symbole. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est classé comme une lettre majuscule. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme une lettre majuscule. |
| static **bool** [IsUpper](./isupper/)(char_t) | Détermine si le caractère spécifié est classé comme une lettre majuscule. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Détermine si le caractère à l'index spécifié dans le tampon de caractères spécifié est classé comme un caractère d'espace blanc. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Détermine si le caractère spécifié est classé comme un caractère d'espace blanc. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Détermine si le caractère à l'index spécifié dans la chaîne spécifiée est classé comme un caractère d'espace blanc. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Convertit le premier et unique caractère de la chaîne spécifiée en une valeur char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Convertit le caractère spécifié en minuscule. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convertit le caractère spécifié en minuscule. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Convertit le caractère spécifié en minuscule. |
| static char_t [ToUpper](./toupper/)(char_t) | Convertit le caractère spécifié en majuscule. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convertit le caractère spécifié en majuscule. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Convertit le caractère spécifié en majuscule. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Tente de convertir une chaîne composée d'un seul caractère en caractère UTF-16. La fonction réussit uniquement lorsque la chaîne d'entrée n'est pas nulle et a une longueur d'exactement un caractère. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)