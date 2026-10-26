---
title: FindAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère tous les éléments qui correspondent aux conditions définies par le prédicat spécifié.
type: docs
weight: 664
url: /fr/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) méthode

Récupère tous les éléments qui correspondent aux conditions définies par le prédicat spécifié.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) pour rechercher des éléments dans |
| match | [System::Predicate](../../predicate/)\<T\> | Un prédicat qui définit les conditions auxquelles les éléments du tableau doivent correspondre |

### Valeur de retour

Un [Array](../) contenant tous les éléments qui correspondent aux conditions définies par le prédicat spécifié, s’ils sont trouvés ; sinon, un [Array](../) vide.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)