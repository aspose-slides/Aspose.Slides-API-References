---
title: ConstrainedCopy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Copie une plage d'éléments d'un System.Array en commençant à la source spécifiée.
type: docs
weight: 716
url: /fr/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) méthode

Copie une plage d'éléments d'un [System.Array](../) en commençant à la source spécifiée.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Tableau source |
| srcIndex | **int64_t** | Indice dans le tableau source désignant le début de la plage d'éléments à copier |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Tableau de destination |
| dstIndex | **int64_t** | Indice dans le tableau de destination où commencer à insérer les éléments copiés |
| count | **int64_t** | Le nombre d'éléments à copier |

## Remarques

IMPLEMENTATION BRUTE TEMPORAIRE SANS AUCUNE CORRECTION !

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)