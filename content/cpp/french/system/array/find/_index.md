---
title: Find()
second_title: Référence de l'API Aspose.Slides pour C++
description: Recherche le premier élément du tableau spécifié qui satisfait les conditions du prédicat spécifié.
type: docs
weight: 651
url: /fr/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) méthode

Recherche le premier élément du tableau spécifié qui satisfait les conditions du prédicat spécifié.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pour rechercher un élément dans |
| match | [System::Predicate](../../predicate/)\<T\> | Un prédicat qui définit les conditions pour faire correspondre les éléments du tableau |

### Valeur de retour

Copie du premier élément du tableau qui satisfait les conditions définies par le prédicat, sinon la valeur par défaut du type T

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)