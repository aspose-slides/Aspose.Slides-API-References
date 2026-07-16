---
title: InsertionSort()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue un tri par insertion sur des paires clé-valeur.
type: docs
weight: 66
url: /fr/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fonction

Effectue un tri par insertion sur des paires clé-valeur.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | La plage de clés à trier |
| values | [Span](../../system/span/)\<TValue\>\& | La plage de valeurs à trier |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fonction pour les clés |

## Voir aussi

* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)