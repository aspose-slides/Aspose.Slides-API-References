---
title: IndexOfAny()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche avant du caractère.
type: docs
weight: 638
url: /fr/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const méthode


Recherche avant du caractère.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| c | char_t | Caractère à rechercher. |
| startIndex | int | Index où commencer la recherche. |

### Valeur de retour

Index de la première position de caractère depuis startIndex ou -1 si non trouvé.

## String::IndexOfAny(const String\&, int) const méthode


Recherche donc tous les caractères de str dans cet objet. Si le premier caractère est trouvé, sa position est renvoyée, sinon il recherche le deuxième et ainsi de suite.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) de caractères à rechercher. L'ordre des caractères est important. |
| startIndex | int | Position où commencer la recherche. |

### Valeur de retour

Index du premier caractère trouvé ou -1 si aucun n'est trouvé.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const méthode


Recherche l'un des caractères fournis dans l'ensemble de la chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis compare le deuxième, etc. Retourne l'index du premier correspondant à l'un des caractères cibles.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |

### Valeur de retour

Index du premier caractère correspondant ou -1 si non trouvé.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const méthode


Recherche l'un des caractères fournis dans la sous-chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis compare le deuxième, etc. Retourne l'index du premier correspondant à l'un des caractères cibles.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |
| startindex | **int32_t** | Index où commencer la recherche. |

### Valeur de retour

Index du premier caractère correspondant ou -1 si non trouvé.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const méthode


Recherche l'un des caractères fournis dans la sous-chaîne. Compare le premier caractère de la chaîne à tous les caractères de anyOf, puis compare le deuxième, etc. Retourne l'index du premier correspondant à l'un des caractères cibles.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |
| startindex | **int32_t** | Index où commencer la recherche. |
| count | **int32_t** | Nombre de caractères à parcourir. |

### Valeur de retour

Index du premier caractère correspondant ou -1 si non trouvé.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)