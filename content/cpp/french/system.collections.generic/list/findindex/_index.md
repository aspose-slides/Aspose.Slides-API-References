---
title: FindIndex()
second_title: Référence API Aspose.Slides pour C++
description: Recherche un élément qui répond à un prédicat spécifique.
type: docs
weight: 404
url: /fr/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) méthode

Recherche un élément qui répond à un prédicat spécifique.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prédicat utilisé pour vérifier les éléments. |

### Valeur de retour

Indice de l'élément correspondant ou -1 si non trouvé.

## List::FindIndex(int, System::Predicate\<T\>) méthode

Recherche un élément qui répond à un prédicat spécifique.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Indice à partir duquel démarrer la recherche. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prédicat utilisé pour vérifier les éléments. |

### Valeur de retour

Indice de l'élément correspondant ou -1 si non trouvé.

## List::FindIndex(int, int, System::Predicate\<T\>) méthode

Recherche un élément qui répond à un prédicat spécifique.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Indice à partir duquel démarrer la recherche. |
| count | int | Nombre d'éléments à parcourir. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prédicat utilisé pour vérifier les éléments. |

### Valeur de retour

Indice de l'élément correspondant ou -1 si non trouvé.

## Voir aussi

* Typedef [Predicate](../../../system/predicate/)
* Classe [List](../)
* Espace de noms [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)