---
title: BinarySearchImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémentation binaire commune.
type: docs
weight: 118
url: /fr/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) fonction

Implémentation binaire commune.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type des éléments dans le span |
| TValue | Type de la valeur à rechercher |
| TCompareFunc | Type de fonction pour la comparaison |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Le span à rechercher |
| value | const TValue\& | La valeur à rechercher |
| compareFunc | TCompareFunc | Fonction qui compare la valeur avec l'élément du span et renvoie **int32_t** (-1, 0, 1) |

### Valeur de retour

Indice de l'élément trouvé ou complément à bits du point d'insertion

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)