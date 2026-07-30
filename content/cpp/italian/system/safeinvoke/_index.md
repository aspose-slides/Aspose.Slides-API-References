---
title: SafeInvoke()
second_title: Riferimento API Aspose.Slides per C++
description: Implementazione della traduzione dell'operatore '?.'.
type: docs
weight: 2653
url: /it/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) funzione


Implementazione della traduzione dell'operatore '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T0 | tipo dell'espressione. |
| T1 | Tipo della lambda che incapsula l'espressione 'WhenTrue'. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expr | T0\&& | valore dell'espressione. |
| func | T1\&& | espressione 'WhenTrue' associata al functor. |

### Valore di ritorno

Se il valore di expr non è nullo, restituisce func chiamato con il suo valore come primo argomento, altrimenti restituisce nullo.

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)