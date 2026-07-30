---
title: operator!=()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se il valore rappresentato dall'oggetto corrente non è nullo.
type: docs
weight: 144
url: /it/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const metodo

Determina se il valore rappresentato dall'oggetto corrente non è nullo.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### Valore restituito

True se il valore rappresentato dall'oggetto corrente non è nullo, altrimenti - false

## Nullable::operator!=(const T1\&) const metodo

Determina se il valore rappresentato dall'oggetto corrente non è uguale al valore specificato.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore con cui confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante al valore con cui confrontare |

### Valore restituito

True se il valore rappresentato dall'oggetto corrente non è uguale al valore specificato, altrimenti - false

## Nullable::operator!=(const Nullable\<T1\>\&) const metodo

Determina se il valore rappresentato dall'oggetto corrente non è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo sottostante dell'oggetto [Nullable](../) con cui confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) con cui confrontare |

### Valore restituito

True se il valore rappresentato dall'oggetto corrente non è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato, altrimenti - false

## Vedi anche

* Classe [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)