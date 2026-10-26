---
title: operator>=()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce sempre false.
type: docs
weight: 183
url: /it/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method


Restituisce sempre false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Valore restituito

Sempre - false

## Nullable::operator>=(const T1\&) const method


Determina se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto specificato applicando [operator>=()](./) a questi valori.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Il tipo sottostante del valore da confrontare con il valore rappresentato dall'oggetto corrente |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante a un oggetto con cui confrontare l'oggetto corrente |

### Valore restituito

True se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto specificato, altrimenti - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method


Determina se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto [Nullable](../) specificato applicando [operator>=()](./) a questi valori.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Il tipo sottostante dell'oggetto [Nullable](../) da confrontare |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) con cui confrontare |

### Valore restituito

True se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto [Nullable](../) specificato, altrimenti - false

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)