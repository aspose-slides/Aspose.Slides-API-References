---
title: LastIndexOf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche arrière d'une sous-chaîne.
type: docs
weight: 651
url: /fr/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const méthode

Recherche arrière d'une sous-chaîne.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |

### Valeur de retour

Indice de la dernière sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, renvoie toujours la longueur de la chaîne.

## String::LastIndexOf(const String\&, System::StringComparison) const méthode

Recherche arrière d'une sous-chaîne.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la dernière sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, renvoie toujours la longueur de la chaîne.

## String::LastIndexOf(const String\&, int, System::StringComparison) const méthode

Recherche arrière d'une sous-chaîne.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la dernière sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, renvoie toujours la longueur de la chaîne.

## String::LastIndexOf(const String\&, int, int, StringComparison) const méthode

Recherche arrière d'une sous-chaîne.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Sous-chaîne à rechercher. |
| startIndex | int | Position dans la chaîne source où commencer la recherche. |
| count | int | Nombre de caractères à parcourir. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Valeur de retour

Indice de la dernière sous-chaîne trouvée ou -1 si non trouvée. Pour une chaîne de recherche vide, renvoie toujours startIndex+count.

## String::LastIndexOf(char_t) const méthode

Recherche arrière d'un caractère.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | Caractère à rechercher. |

### Valeur de retour

Indice de la dernière position de caractère ou -1 si non trouvé.

## String::LastIndexOf(char_t, int32_t) const méthode

Recherche arrière d'un caractère.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | Caractère à rechercher. |
| startIndex | **int32_t** | Index où commencer la recherche. |

### Valeur de retour

Indice de la dernière position de caractère depuis startIndex ou -1 si non trouvé.

## String::LastIndexOf(char_t, int32_t, int32_t) const méthode

Recherche arrière d'un caractère.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | char_t | Caractère à rechercher. |
| startIndex | **int32_t** | Index où commencer la recherche. |
| count | **int32_t** | Nombre de caractères à parcourir |

### Valeur de retour

Indice de la dernière position de caractère depuis startIndex ou -1 si non trouvé.

## Voir aussi

* Enum [StringComparison](../../stringcomparison/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)