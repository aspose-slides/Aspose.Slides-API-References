---
title: CoalesceInternal()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementazione della traduzione dell'operatore '??' per tipi non nullable. Sovraccarico per il caso in cui RT2 è convertibile in RT1.
type: docs
weight: 157
url: /it/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metodo

Implementazione della traduzione dell'operatore '??' per tipi non nullable. Sovraccarico per il caso in cui RT2 è convertibile in RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T0 | Tipo valore LHS. |
| T1 | Tipo della lambda che incapsula l'espressione RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | RT1 | Valore LHS. |
| func | F | Espressione RHS. |

### Valore di ritorno

Se il valore LHS non è null, restituisce LHS, altrimenti calcola l'espressione RHS e restituisce il risultato.

## Vedi anche

* Classe [ObjectExt](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)