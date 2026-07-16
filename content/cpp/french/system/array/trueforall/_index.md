---
title: TrueForAll()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si tous les éléments du tableau spécifié satisfont les conditions définies par le prédicat spécifié.
type: docs
weight: 677
url: /fr/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) méthode


Détermine si tous les éléments du tableau spécifié satisfont les conditions définies par le prédicat spécifié.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) éléments dont il faut vérifier les conditions |
| match | [System::Predicate](../../predicate/)\<T\> | Un prédicat qui définit les conditions à vérifier pour les éléments du tableau |

### Valeur de retour

true si tous les éléments du tableau arr satisfont les conditions définies par le prédicat match, sinon false

## Voir également

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)