---
title: Coalesce()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementazione della traduzione dell'operatore '??' per tipi non nullabili.
type: docs
weight: 170
url: /it/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metodo

Implementazione della traduzione dell'operatore '??' per tipi non nullabili.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T0 | Tipo di valore LHS. |
| T1 | Tipo del lambda che incapsula l'espressione RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T0 | Valore LHS. |
| func | T1 | Espressione RHS. |

### Valore restituito

Se il valore LHS non è null, restituisce LHS, altrimenti calcola l'espressione RHS e restituisce il risultato.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metodo

Implementazione della traduzione dell'operatore '??' per tipi nullabili.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T0 | Tipo di valore LHS. |
| T1 | Tipo del lambda che incapsula l'espressione RHS. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Valore LHS. |
| func | T1 | Espressione RHS. |

### Valore restituito

Se il valore LHS non è null, restituisce LHS, altrimenti calcola l'espressione RHS e restituisce il risultato.

## Vedi anche

* Classe [ObjectExt](../)
* Classe [Nullable](../../nullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)