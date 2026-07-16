---
title: PickPivotAndPartition()
second_title: Référence API Aspose.Slides pour C++
description: Sélectionne le pivot et partitionne les paires clé-valeur pour le tri rapide.
type: docs
weight: 105
url: /fr/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fonction

Sélectionne le pivot et partitionne les paires clé-valeur pour le tri rapide.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | L'étendue des clés à partitionner |
| values | [Span](../../system/span/)\<TValue\>\& | L'étendue des valeurs à partitionner |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fonction pour les clés |

### Valeur retournée

L'indice du pivot après partitionnement

## Voir aussi

* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)