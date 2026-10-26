---
title: SwapIfGreaterWithValues()
second_title: Référence de l'API Aspose.Slides pour C++
description: Échange les paires clé-valeur si la condition de comparaison est remplie.
type: docs
weight: 53
url: /fr/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) fonction

Échange les paires clé-valeur si la condition de comparaison est remplie.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Le type des clés |
| TValue | Le type des valeurs |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | La tranche de clés |
| values | [Span](../../system/span/)\<TValue\>\& | La tranche de valeurs |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fonction pour les clés |
| i | **int32_t** | Premier indice à comparer |
| j | **int32_t** | Deuxième indice à comparer |

## Voir aussi

* Classe [Span](../../system/span/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)