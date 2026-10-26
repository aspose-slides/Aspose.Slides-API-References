---
title: AsSpan()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un span à partir d'un tableau.
type: docs
weight: 1
url: /fr/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) fonction


Crée un span à partir d'un tableau.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Le type des éléments du tableau. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Le tableau source. |
| start | **int32_t** | L'indice de départ dans le tableau. |
| length | **int32_t** | La longueur du span. |

### Valeur de retour

Span<T> couvrant la partie spécifiée du tableau.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) fonction


Crée un span en lecture seule à partir d'une chaîne.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | La chaîne source. |
| start | **int32_t** | L'indice de départ dans la chaîne. |
| length | **int32_t** | La longueur du span. |

### Valeur de retour

ReadOnlySpan<char16_t> couvrant la partie spécifiée de la chaîne.

## Voir aussi

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)