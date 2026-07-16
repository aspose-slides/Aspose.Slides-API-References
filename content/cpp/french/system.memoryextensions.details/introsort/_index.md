---
title: IntroSort()
second_title: Référence API Aspose.Slides pour C++
description: Implémentation interne de l'algorithme introsort pour les paires clé-valeur.
type: docs
weight: 40
url: /fr/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) fonction

Implémentation interne de l'algorithme introsort pour les paires clé-valeur.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | La tranche de clés à trier |
| values | [Span](../../system/span/)\<TValue\>\& | La tranche de valeurs à trier |
| depthLimit | **int32_t** | Profondeur maximale de récursion avant le passage au heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fonction pour les clés |

## Voir aussi

* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)