---
title: String
second_title: Référence de l'API Aspose.Slides pour C++
description: "Classe String utilisée dans l'ensemble de la bibliothèque. C'est un substitut à System.String de C# lors de la traduction du code. Pour des raisons d'optimisation, elle n'est pas considérée comme une sous-classe d'Object. Ce type doit être alloue sur la pile et passe aux fonctions par valeur ou par reference. N'utilisez jamais la classe System::SmartPtr pour gerer les objets de ce type."
type: docs
weight: 1249
url: /fr/system/string/
---
## String classe

[String](./) classe utilisée dans l'ensemble de la bibliothèque. C’est un substitut à C# [System.String](./) lors de la traduction du code. Pour des raisons d'optimisation, il n'est pas considéré comme une sous-classe de [Object](../object/). Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

```cpp
class String
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) est un type valeur côté C++ qui implémente implicitement (sans héritage) certaines interfaces. |
| const UChar * [begin](./begin/)() const | Renvoie un pointeur vers le début du tampon de chaîne réel. Ne réalloue jamais rien. Ne garantit pas que le tampon soit nul-terminé. |
| [String](./) [Clone](./clone/)() const | Crée une copie de la chaîne actuelle. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compare deux sous-chaînes avec les opérateurs inférieur, égal, supérieur. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Compare deux chaînes avec les opérateurs inférieur, égal, supérieur en mode ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Compare deux chaînes avec les opérateurs inférieur, égal, supérieur en mode ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Compare deux chaînes dans le style « less-equals-more ». Utilise la culture actuelle. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Concatène des chaînes. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Concatène des chaînes. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatène des chaînes. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatène des chaînes. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Vérifie si str est une sous-chaîne de la chaîne actuelle. |
| **bool** [Contains](./contains/)(char16_t) const | Vérifie si la chaîne contient le caractère donné. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Crée une copie de la chaîne. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Copie les caractères de la chaîne dans les éléments de tableau existants. Aucun redimensionnement n'est effectué. |
| const UChar * [end](./end/)() const | Renvoie un pointeur vers la fin du tampon de chaîne réel. Ne réalloue jamais rien. Ne garantit pas que le tampon soit nul-terminé. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Vérifie si la chaîne se termine par la sous-chaîne spécifiée. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Vérifie si la chaîne se termine par la sous-chaîne spécifiée. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Vérifie si la chaîne se termine par la sous-chaîne spécifiée. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) comparaison d'égalité. Plusieurs modes fournis par l'énumération StringComparison sont pris en charge. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) comparaison d'égalité. Utilise le mode de comparaison [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Compare deux chaînes avec égalité en utilisant le mode de comparaison ordinal. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compare deux chaînes avec égalité. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Essaie de convertir un [String](./) en une chaîne ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formate la chaîne dans le style C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formate la chaîne dans le style C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formate la chaîne dans le style C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formate la chaîne dans le style C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formate la chaîne dans le style C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Crée [String](./) à partir d’une chaîne ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Crée [String](./) à partir d’une chaîne ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Crée [String](./) à partir d’une chaîne ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Crée [String](./) à partir d’une chaîne utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Crée [String](./) à partir d’une chaîne utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Crée [String](./) à partir d’une chaîne utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Crée [String](./) à partir d’une chaîne utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Crée [String](./) à partir d’une chaîne utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Crée [String](./) à partir d’une chaîne utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Crée [String](./) à partir d’une chaîne large. |
| int [get_Length](./get_length/)() const | Obtient la longueur de la chaîne. |
| int [GetHashCode](./gethashcode/)() const | Calcule le hachage de la chaîne contenue. Implémenté dans ICU, ne correspond pas aux hachages en C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Recherche avant d'une sous-chaîne. |
| int [IndexOf](./indexof/)(char_t, int) const | Recherche avant d'un caractère. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Recherche avant d'un caractère dans une sous-chaîne. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Recherche avant d'une sous-chaîne. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Recherche avant d'une sous-chaîne. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Recherche avant d'une sous-chaîne. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Recherche avant d'une sous-chaîne. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Recherche avant d'un caractère. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Recherche donc tous les caractères de str dans celle-ci. Si le premier caractère est trouvé, sa position est renvoyée, sinon il recherche le deuxième, etc. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Recherche n'importe lequel des caractères fournis dans l'ensemble de la chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis le deuxième, etc. Retourne l'index du premier qui correspond à l'un des caractères cible. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Recherche n'importe lequel des caractères fournis dans la sous-chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis le deuxième, etc. Retourne l'index du premier qui correspond à l'un des caractères cible. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Recherche n'importe lequel des caractères fournis dans la sous-chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis le deuxième, etc. Retourne l'index du premier qui correspond à l'un des caractères cible. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Insère une sous-chaîne à la position spécifiée. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet string est du type spécifié par [TypeInfo](../typeinfo/) passé. |
| **bool** [IsAsciiString](./isasciistring/)() const | Indique si un [String](./) ne contient que des symboles ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Vérifie si la chaîne est à la fois non nulle et vide. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Vérifie si la chaîne unicode est normalisée en utilisant la forme de normalisation spécifiée. |
| **bool** [IsNull](./isnull/)() const | Vérifie si la chaîne est considérée comme nulle. [String](./) est nul uniquement si elle est construite via le constructeur [String()](./string/), déplacée, copiée ou assignée depuis une chaîne nulle ou si la méthode [reset()](./reset/) a été appelée. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Vérifie si la chaîne est vide ou considérée comme nulle. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Vérifie si la chaîne passée est nulle ou vide. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Indique si une chaîne spécifiée est nulle, vide ou ne contient que des caractères d'espacement. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Concatène le tableau en utilisant la chaîne comme séparateur. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Concatène le tableau en utilisant la chaîne comme séparateur. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Concatène le tableau en utilisant la chaîne comme séparateur. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Concatène le tableau en utilisant la chaîne comme séparateur. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Recherche arrière d'une sous-chaîne. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Recherche arrière d'une sous-chaîne. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Recherche arrière d'une sous-chaîne. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Recherche arrière d'une sous-chaîne. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Recherche arrière d'un caractère. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Recherche arrière d'un caractère. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Recherche arrière d'un caractère. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Recherche n'importe lequel des caractères fournis dans l'ensemble de la chaîne en sens inverse. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis le précédent, etc. Retourne l'index de la première correspondance trouvée. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Recherche n'importe lequel des caractères fournis dans la sous-chaîne en sens inverse. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis le précédent, etc. Retourne l'index de la première correspondance trouvée. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Recherche n'importe lequel des caractères fournis dans la sous-chaîne en sens inverse. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis le précédent, etc. Retourne l'index de la première correspondance trouvée. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalise la chaîne unicode en utilisant la forme de normalisation spécifiée. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Convertit la chaîne en span en lecture seule. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Opérateur de comparaison d’inégalité. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Vérifie si la chaîne n’est pas nulle. Applique la même logique que l’appel [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) opérateur de concaténation. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) concaténation avec littéral de chaîne ou pointeur de chaîne de caractères. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Ajoute un caractère à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(int) const | Ajoute la représentation sous forme de chaîne d’une valeur entière à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Ajoute la représentation sous forme de chaîne d’une valeur entière non signée à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Ajoute la représentation sous forme de chaîne d’un nombre à virgule flottante à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Ajoute la représentation sous forme de chaîne d’une valeur entière à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Ajoute la représentation sous forme de chaîne d’un objet de type référence à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Ajoute la représentation sous forme de chaîne d’un objet de type référence à la fin de la chaîne. |
| [String](./) [operator+](./operator_plus/)(T) const | Ajoute la représentation sous forme de chaîne d’une valeur booléenne à la fin de la chaîne. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Opérateur d’affectation de concaténation. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Opérateur d’affectation de concaténation. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Compare les chaînes selon l'ordre. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Opérateur d’affectation. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Opérateur d’affectation par déplacement. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Opérateur de comparaison d’égalité. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si la chaîne est nulle. Applique la même logique que l’appel [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Compare les chaînes selon l'ordre. |
| char_t [operator[]](./operator[]/)(int) const | Obtient le caractère à la position spécifiée. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Ajoute du remplissage à gauche de la chaîne originale. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Ajoute du remplissage à droite de la chaîne originale. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Renvoie un itérateur inverse vers le dernier caractère (s’il existe) du tampon de chaîne réel. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extrait tout sauf la sous-chaîne de la chaîne actuelle. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Renvoie un itérateur inverse vers avant le premier caractère (s’il existe) du tampon de chaîne réel. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Remplace toutes les occurrences du caractère dans la chaîne. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Remplace toutes les occurrences de lookup dans cette chaîne. |
| [String](./)\& [reset](./reset/)() | Définit la chaîne à null. C’est analogue à « string_variable_name = null » en C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Définit le caractère à la position spécifiée. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par caractère. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par caractère. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par l’un des deux caractères. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par l’un des caractères spécifiés. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par l’un des caractères spécifiés. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par sous-chaîne. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par sous-chaîne. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par sous-chaîne. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divise la chaîne par sous-chaîne. Actuellement, ne supporte qu’un tableau de séparateurs contenant zéro ou un élément. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Vérifie si la chaîne commence par la sous-chaîne spécifiée. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Vérifie si la chaîne commence par la sous-chaîne spécifiée. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Vérifie si la chaîne commence par la sous-chaîne spécifiée. |
|  [String](./string/)() | Constructeur par défaut. Crée un objet string considéré comme null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Construit une chaîne à partir d’un littéral de chaîne. Considère le littéral comme une chaîne terminée par nul, calcule la longueur cible de la chaîne en fonction de la taille du littéral. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Construit une chaîne à partir d’un pointeur de chaîne de caractères. Traite la chaîne pointée comme terminée par nul, calcule la longueur cible de la chaîne en fonction du caractère nul. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Construit une chaîne à partir d’un littéral de chaîne. Considère le littéral comme une chaîne terminée par nul en UTF8, calcule la longueur cible de la chaîne en fonction de la taille du littéral. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Construit une chaîne à partir d’un pointeur de chaîne de caractères. Traite la chaîne pointée comme terminée par nul en UTF8, calcule la longueur cible de la chaîne en fonction du caractère nul. |
|  [String](./string/)(const char16_t *, int) | Construit une chaîne à partir d’un pointeur de chaîne de caractères et d’une longueur explicite. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Initialise une nouvelle instance de la classe [System.String](./) avec les caractères Unicode indiqués dans le span en lecture seule spécifié. |
|  [String](./string/)(const char *, int) | Construit une chaîne à partir d’un pointeur de chaîne de caractères et d’une longueur explicite. |
|  [String](./string/)(const char16_t *, int, int) | Construit une chaîne à partir d’un pointeur de chaîne de caractères à partir de la position de départ en utilisant la longueur. |
| explicit  [String](./string/)(const char16_t, int) | Constructeur de remplissage. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Constructeur nullptr. Déclaré comme modèle pour résoudre les priorités avec d’autres constructeurs modèle. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Construit une chaîne à partir d’un littéral widestring. Considère le littéral comme une chaîne terminée par nul, calcule la longueur cible de la chaîne en fonction de la taille du littéral. La conversion depuis **wchar_t** est coûteuse sur certaines plateformes, aucune conversion implicite n’est autorisée. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Construit une chaîne à partir d’un pointeur de chaîne widecharacter. Traite la chaîne pointée comme terminée par nul, calcule la longueur cible de la chaîne en fonction du caractère nul. La conversion depuis **wchar_t** est coûteuse sur certaines plateformes, aucune conversion implicite n’est autorisée. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Construit une chaîne à partir d’un pointeur de chaîne widecharacter et d’une longueur explicite. La conversion depuis **wchar_t** est coûteuse sur certaines plateformes, aucune conversion implicite n’est autorisée. |
| explicit  [String](./string/)(const **wchar_t**, int) | Constructeur de remplissage. La conversion depuis **wchar_t** est coûteuse sur certaines plateformes, aucune conversion implicite n’est autorisée. |
|  [String](./string/)(const [String](./)\&) | Constructeur de copie. |
|  [String](./string/)([String](./)\&&) | Constructeur de déplacement. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Convertit le tableau complet de caractères en chaîne. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Convertit une sous-plage du tableau de caractères en chaîne. Si les paramètres sont hors des limites du tableau, une chaîne vide est construite. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Enveloppe UnicodeString dans [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Constructeur de déplacement. |
| explicit  [String](./string/)(const std::wstring\&) | Crée [String](./) à partir d’une chaîne large. |
| explicit  [String](./string/)(const std::u16string\&) | Crée [String](./) à partir d’une chaîne utf16. |
| explicit  [String](./string/)(const std::string\&) | Crée [String](./) à partir d’une chaîne std::string présentée au format UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Crée [String](./) à partir d’une chaîne std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extrait une sous-chaîne. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extrait une sous-chaîne. |
| std::string [ToAsciiString](./toasciistring/)() const | Convertit la chaîne en std::string. Utilise l’encodage ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Convertit la chaîne ou la sous-chaîne en tableau d'octets. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Convertit la chaîne ou la sous-chaîne en tableau de caractères. |
| [String](./) [ToLower](./tolower/)() const | Convertit tous les caractères de la chaîne en minuscules. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convertit tous les caractères de la chaîne en minuscules en utilisant une culture spécifique. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Convertit tous les caractères de la chaîne en minuscules en utilisant la culture invariante. |
| [String](./) [ToString](./tostring/)() const | Wrapper pour gérer la classe [String](./) dans les contextes où [ToString()](./tostring/) est appelé sur des objets de type valeur. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper pour gérer la classe [String](./) dans les contextes où [ToString()](./tostring/) est appelé sur des objets de type valeur. |
| std::u16string [ToU16Str](./tou16str/)() const | Convertit la chaîne en std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Convertit la chaîne en std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Convertit tous les caractères de la chaîne en majuscules. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convertit tous les caractères de la chaîne en majuscules en utilisant une culture spécifique. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Convertit tous les caractères de la chaîne en majuscules en utilisant la culture invariante. |
| std::string [ToUtf8String](./toutf8string/)() const | Convertit la chaîne en std::string. Utilise l’encodage UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Convertit la chaîne en std::wstring. |
| [String](./) [Trim](./trim/)() const | Supprime tous les caractères d'espacement du début et de la fin de la chaîne. |
| [String](./) [Trim](./trim/)(char_t) const | Supprime toutes les occurrences du caractère passé du début et de la fin de la chaîne. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Supprime toutes les occurrences des caractères passés du début et de la fin de la chaîne. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Supprime toutes les occurrences des caractères passés du début et de la fin de la chaîne. |
| [String](./) [TrimEnd](./trimend/)() const | Supprime tous les caractères d'espacement de la fin de la chaîne. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Supprime toutes les occurrences du caractère passé de la fin de la chaîne. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Supprime toutes les occurrences des caractères passés de la fin de la chaîne. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Supprime toutes les occurrences des caractères passés de la fin de la chaîne. |
| [String](./) [TrimStart](./trimstart/)() const | Supprime tous les caractères d'espacement du début de la chaîne. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Supprime toutes les occurrences du caractère passé du début de la chaîne. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Supprime toutes les occurrences des caractères passés du début de la chaîne. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Supprime toutes les occurrences des caractères passés du début de la chaîne. |
| const UChar * [u_str](./u_str/)() const | Renvoie un tampon null-terminé au style ICU. Peut réallouer la chaîne. |
|  [~String](./~string/)() | Destructeur. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Chaîne vide. |
| static [Null](./null/) | Chaîne nulle. |

## Alias de type

| Alias de type | Description |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Type d'itérateur inverse. |

## Remarques



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Construire une chaîne à partir du tableau de caractères et l'afficher.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Construire une chaîne à partir du tableau d'octets et l'afficher.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Supprimer les espaces de la chaîne ci-dessous et l'afficher.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Afficher le nombre de mots dans la chaîne.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Ce code d'exemple produit la sortie suivante :
bonjour
monde
"This string contains whitespaces in the beginning and at the end."
Nombre de mots : 11
*/
```


## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)