---
title: TryGetFirst()
second_title: Riferimento API Aspose.Slides per C++
description: Prova a ottenere il primo elemento della collezione.
type: docs
weight: 248
url: /it/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) function

Prova a ottenere il primo elemento della collezione.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Il tipo degli elementi della collezione. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collezione da cui acquisire un elemento. |
| found | **bool**\& | Il parametro di output. Restituisce true se la collezione contiene almeno un elemento. In caso contrario viene restituito false. |

### Return Value

Restituisce il primo elemento della collezione. Viene restituito il valore predefinito del tipo quando la collezione è vuota.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) function

Prova a ottenere il primo elemento della collezione che soddisfa la funzione predicato.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Il tipo degli elementi della collezione. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collezione da cui acquisire un elemento. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | La funzione predicato. |
| found | **bool**\& | Il parametro di output. Restituisce true se la collezione contiene almeno un elemento. In caso contrario viene restituito false. |

### Return Value

Restituisce il primo elemento della collezione. Viene restituito il valore predefinito del tipo quando non viene trovato alcun elemento che soddisfi la funzione predicato specificata.

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [Func](../../system/func/)
* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)