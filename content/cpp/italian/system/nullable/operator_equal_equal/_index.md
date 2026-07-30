---
title: operator==()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il valore rappresentato dall'oggetto corrente è null.
type: docs
weight: 118
url: /it/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metodo


Determina se il valore rappresentato dall'oggetto corrente è null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è null, altrimenti - false

## Nullable::operator==(const T1\&) const metodo


Determina se il valore rappresentato dall'oggetto corrente è uguale al valore specificato.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore da confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante al valore da confrontare |

### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è uguale al valore specificato, altrimenti - false

## Nullable::operator==(const Nullable\<T1\>\&) const metodo


Determina se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo sottostante dell'oggetto [Nullable](../) da confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) da confrontare |

### Valore di ritorno

True se il valore rappresentato dall'oggetto corrente è uguale al valore rappresentato dall'oggetto [Nullable](../) specificato, altrimenti - false

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)