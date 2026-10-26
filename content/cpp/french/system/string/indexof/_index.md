---
title: IndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche en avant d'une sous-chaîne.
type: docs
weight: 625
url: /fr/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const méthode

Recherche avant d'une sous-chaîne.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la première sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, retourne toujours 0.

## String::IndexOf(char_t, int) const méthode

Recherche avant d'un caractère.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Caractère à rechercher. |
| startIndex | int | Index à partir duquel commencer la recherche. |

### Valeur de retour

Indice de la première position de caractère depuis startIndex ou -1 si non trouvé.

## String::IndexOf(char_t, int, int) const méthode

Recherche avant d'un caractère dans une sous-chaîne.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Caractère à rechercher. |
| startIndex | int | Index à partir duquel commencer la recherche. |
| count | int | Nombre de caractères à parcourir. |

### Valeur de retour

Indice de la première position de caractère depuis startIndex ou -1 si non trouvé.

## String::IndexOf(const String\&, int) const méthode

Recherche avant d'une sous-chaîne.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |

### Valeur de retour

Indice de la première sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, retourne toujours startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const méthode

Recherche avant d'une sous-chaîne.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la première sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, retourne toujours startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const méthode

Recherche avant d'une sous-chaîne.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |
| count | int | nombre de caractères à parcourir. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la première sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, retourne toujours startIndex.

## String::IndexOf(const String\&, int, int) const méthode

Recherche avant d'une sous-chaîne.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |
| count | int | nombre de caractères à parcourir. |

### Valeur de retour

Indice de la première sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, retourne toujours startIndex.

## Voir aussi

* Enum [StringComparison](../../stringcomparison/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)