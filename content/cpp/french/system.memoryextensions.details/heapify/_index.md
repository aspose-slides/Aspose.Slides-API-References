---
title: Heapify()
second_title: Référence de l'API Aspose.Slides pour C++
description: Maintient la propriété du tas pour les paires clé-valeur.
type: docs
weight: 92
url: /fr/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Maintient la propriété du tas pour les paires clé-valeur.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys in the heap |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values in the heap |
| n | **int32_t** | Taille du tas |
| i | **int32_t** | Index à partir duquel rétablir le tas |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fonction pour les clés |

## Voir aussi

* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)