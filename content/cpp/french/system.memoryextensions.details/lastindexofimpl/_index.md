---
title: LastIndexOfImpl()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trouve le dernier indice d'une valeur dans un span.
type: docs
weight: 14
url: /fr/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function


Trouve le dernier indice d'une valeur dans un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type des éléments du span |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) à rechercher |
| length | **int32_t** | Longueur dans laquelle rechercher |
| value | const T\& | Valeur à trouver |

### Valeur de retour

Dernier indice de la valeur, ou -1 si non trouvé

## Voir aussi

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Espace de noms [System::MemoryExtensions::Details](../)
* Bibliothèque [Aspose.Slides](../../)