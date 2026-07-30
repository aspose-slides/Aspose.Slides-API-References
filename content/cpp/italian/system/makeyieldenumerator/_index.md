---
title: MakeYieldEnumerator()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un IEnumerator da una funzione yield.
type: docs
weight: 2432
url: /it/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction<T>&) funzione

Crea un IEnumerator da una funzione yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nella sequenza |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fnc | const Details::YieldFunction<T>& | La funzione yield da eseguire |

### Valore restituito

Puntatore condiviso a IEnumerator

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerator](../../system.collections.generic/ienumerator/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)