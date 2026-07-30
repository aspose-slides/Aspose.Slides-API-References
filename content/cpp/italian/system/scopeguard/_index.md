---
title: ScopeGuard
second_title: Riferimento API di Aspose.Slides per C++
description: La classe di servizio che fornisce servizi per eseguire un particolare oggetto funzione quando un'istanza della classe esce dal scope.
type: docs
weight: 1886
url: /it/system/scopeguard/
---
## ScopeGuard struct

La classe di servizio che fornisce servizi per eseguire un particolare oggetto funzione quando un'istanza della classe esce dal scope.

```cpp
template<typename F>class ScopeGuard
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| F | Il tipo dell'oggetto funzione invocato dalle istanze della classe ScopedGuard |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Disable](./disable/)() | Disabilita l'invocazione della guardia. |
|  [ScopeGuard](./scopeguard/)(F) | Costruisce un'istanza configurata per invocare l'oggetto funzione specificato. |
|  [~ScopeGuard](./~scopeguard/)() | Invoca l'oggetto funzione passato al costruttore. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)