---
title: TryGetLast()
second_title: Riferimento API di Aspose.Slides per C++
description: Prova a ottenere l'ultimo elemento della collezione.
type: docs
weight: 261
url: /it/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) function

Prova a ottenere l'ultimo elemento della collezione.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi della collezione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | La collezione da cui acquisire un elemento. |
| found | **bool**\& | Il parametro di output. Restituisce true quando la collezione contiene almeno un elemento. Altrimenti restituisce false. |

### Valore di ritorno

Restituisce l'ultimo elemento della collezione. Viene restituito il valore predefinito del tipo quando la collezione è vuota.

## Vedi anche

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Spazio dei nomi [System::Collections::Generic::Details](../)
* Libreria [Aspose.Slides](../../)