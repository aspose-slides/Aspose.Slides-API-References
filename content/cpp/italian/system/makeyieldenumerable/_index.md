---
title: MakeYieldEnumerable()
second_title: Aspose.Slides per C++ Riferimento API
description: Crea un IEnumerable da una funzione yield.
type: docs
weight: 2419
url: /it/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) funzione

Crea un IEnumerable da una funzione yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nella sequenza |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La funzione yield da eseguire |

### Valore di ritorno

Puntatore condiviso a IEnumerable

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)