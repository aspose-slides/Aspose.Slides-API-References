---
title: MakeScopeGuard()
second_title: Riferimento API di Aspose.Slides per C++
description: Una funzione di fabbrica che crea istanze della classe ScopedGuard.
type: docs
weight: 2809
url: /it/system/makescopeguard/
---
## System::MakeScopeGuard(F) funzione

Una funzione di fabbrica che crea istanze della classe ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| The | tipo dell'oggetto funzione da invocare dall'oggetto ScopedGuard costruito |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | F | L'oggetto funzione da passare al costruttore della classe ScopedGuard. |

### Valore di ritorno

Una nuova istanza della classe ScopedGuard

## Vedi anche

* Struct [ScopeGuard](../scopeguard/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)