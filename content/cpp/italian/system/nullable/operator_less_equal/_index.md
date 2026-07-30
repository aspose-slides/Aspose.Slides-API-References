---
title: operator<=()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce sempre false.
type: docs
weight: 196
url: /it/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const metodo

Restituisce sempre false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const metodo

Determina se il valore rappresentato dall'oggetto corrente è minore o uguale al valore specificato applicando [operator<=()](./) a questi valori.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore con cui confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante al valore con cui confrontare |

### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è minore o uguale al valore specificato, altrimenti - false

## Nullable::operator<=(const Nullable\<T1\>\&) const metodo

Determina se il valore rappresentato dall'oggetto corrente è minore o uguale al valore rappresentato dall'oggetto [Nullable](../) specificato applicando [operator<=()](./) a questi valori.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo sottostante dell'oggetto [Nullable](../) con cui confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) con cui confrontare |

### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è minore o uguale al valore rappresentato dall'oggetto [Nullable](../) specificato, altrimenti - false

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)