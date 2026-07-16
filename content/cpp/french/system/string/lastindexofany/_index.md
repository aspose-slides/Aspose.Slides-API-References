---
title: LastIndexOfAny()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche l'un des caractères fournis dans l'ensemble de la chaîne en remontant. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis compare le précédent et ainsi de suite. Retourne l'indice de la première correspondance trouvée.
type: docs
weight: 664
url: /fr/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

Recherche l'un des caractères fournis dans la chaîne entière en remontant. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis compare le précédent et ainsi de suite. Retourne l'indice de la première correspondance trouvée.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |

### Valeur de retour

Indice du dernier caractère correspondant ou -1 si non trouvé.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

Recherche l'un des caractères fournis dans la sous-chaîne en remontant. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis compare le précédent et ainsi de suite. Retourne l'indice de la première correspondance trouvée.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |
| startindex | **int32_t** | Indice à partir duquel commencer la recherche. |

### Valeur de retour

Indice du dernier caractère correspondant ou -1 si non trouvé.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

Recherche l'un des caractères fournis dans la sous-chaîne en remontant. Compare le dernier caractère de la chaîne à tous les caractères de anyOf, puis compare le précédent et ainsi de suite. Retourne l'indice de la première correspondance trouvée.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caractères à rechercher. L'ordre n'a pas d'importance. |
| startindex | **int32_t** | Indice à partir duquel commencer la recherche. |
| count | **int32_t** | Nombre de caractères à parcourir. |

### Valeur de retour

Indice du dernier caractère correspondant ou -1 si non trouvé.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)