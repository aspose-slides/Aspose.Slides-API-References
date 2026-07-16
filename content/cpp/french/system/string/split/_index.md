---
title: Split()
second_title: Référence de l'API Aspose.Slides pour C++
description: Divise la chaîne selon le caractère.
type: docs
weight: 768
url: /fr/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const méthode


Divise la chaîne selon le caractère.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | char_t | Caractère par lequel diviser la chaîne. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(char_t, int32_t, StringSplitOptions) const méthode


Divise la chaîne selon le caractère.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | char_t | Caractère par lequel diviser la chaîne. |
| count | **int32_t** | Nombre maximum de sous-chaînes à renvoyer. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(char_t, char_t, StringSplitOptions) const méthode


Divise la chaîne selon l'un des deux caractères.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorA | char_t | Premier caractère par lequel diviser la chaîne. |
| separatorB | char_t | Second caractère par lequel diviser la chaîne. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const méthode


Divise la chaîne selon l'un des caractères spécifiés.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères séparateurs. Si vide, tout caractère d’espace est considéré comme séparateur. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const méthode


Divise la chaîne selon l'un des caractères spécifiés.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères séparateurs. Si vide, tout caractère d’espace est considéré comme séparateur. |
| count | **int32_t** | Nombre maximum de sous-chaînes à renvoyer. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const String\&, StringSplitOptions) const méthode


Divise la chaîne selon la sous-chaîne.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | Sous-chaîne servant de séparateur. Si vide, le caractère d’espace agit comme séparateur. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const String\&, int, StringSplitOptions) const méthode


Divise la chaîne selon la sous-chaîne.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | Sous-chaîne servant de séparateur. Si vide, le caractère d’espace agit comme séparateur. |
| count | int | Nombre maximal d’éléments dans le tableau de divisions. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const méthode


Divise la chaîne selon la sous-chaîne.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de chaînes séparatrices. Si vide, aucune division n’est effectuée. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const méthode


Divise la chaîne selon la sous-chaîne. Actuellement, ne prend en charge que les tableaux de séparateurs de zéro ou un élément.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de chaînes séparatrices. Si vide, aucune division n’est effectuée. |
| count | int | Nombre maximal d’éléments dans le tableau de divisions. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Options de division. |

### Valeur de retour

[Array](../../array/) de sous-chaînes.

## Voir aussi

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)