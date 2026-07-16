---
title: FindIndex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche le premier élément dans le tableau spécifié qui satisfait les conditions du prédicat spécifié.
type: docs
weight: 638
url: /fr/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) méthode

Recherche le premier élément dans le tableau spécifié qui satisfait les conditions du prédicat spécifié.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pour rechercher un élément dans |
| match | [System::Predicate](../../predicate/)\<T\> | Un prédicat qui définit les conditions pour comparer les éléments du tableau |

### Valeur de retour

L'index du premier élément du tableau qui satisfait les conditions définies par le prédicat, sinon -1

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)