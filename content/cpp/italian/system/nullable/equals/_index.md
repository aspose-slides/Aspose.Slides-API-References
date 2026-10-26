---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto Nullable specificato.
type: docs
weight: 131
url: /it/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metodo

Determina se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo di base dell'oggetto [Nullable](../) da confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante all'oggetto [Nullable](../) da confrontare |

### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato, altrimenti - false

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)