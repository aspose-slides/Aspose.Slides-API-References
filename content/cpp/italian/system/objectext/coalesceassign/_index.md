---
title: CoalesceAssign()
second_title: Aspose.Slides per C++ Riferimento API
description: Implementazione della traduzione dell'operatore '??='.
type: docs
weight: 183
url: /it/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metodo

Implementazione della traduzione dell'operatore '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T0 | Tipo di valore LHS. |
| T1 | Tipo di lambda che incapsula l'espressione RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T0\& | Valore LHS. |
| func | T1 | Espressione RHS. |

### Valore di ritorno

Se il valore LHS non è nullo, restituisce LHS; altrimenti calcola l'espressione RHS e restituisce il risultato.

## Vedi anche

* Classe [ObjectExt](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)