---
title: SequenceEqualImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si deux spans sont égaux à partir des positions spécifiées.
type: docs
weight: 27
url: /fr/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) fonction

Vérifie si deux spans sont égaux à partir des positions spécifiées.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type of elements in spans |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Premier span |
| start | const **int32_t** | Indice de départ dans le premier span |
| length | **int32_t** | Nombre d'éléments à comparer |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Deuxième span |

### Valeur de retour

true si les plages spécifiées sont égales, false sinon

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)