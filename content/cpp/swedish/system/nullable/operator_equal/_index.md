---
title: operator=()
second_title: Aspose.Slides för C++ API-referens
description: Tilldelar null till det aktuella objektet.
type: docs
weight: 14
url: /sv/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metod


Tilldelar null till det aktuella objektet.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Returvärde

Ett [Nullable](../)-objekt som representerar nullvärde.

## Nullable::operator=(const T1\&) metod


Ersätter objektets för närvarande representerade värde med det angivna.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| The | typ av det nya värdet som ska representeras av det aktuella objektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T1\& | Det nya värdet som ska representeras av det aktuella objektet |

### Returvärde

En referens till sig själv

## Nullable::operator=(const Nullable\<T1\>\&) metod


Ersätter objektets för närvarande representerade värde med det angivna.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| The | typ av det nya värdet som ska representeras av det aktuella objektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Det nya värdet som ska representeras av det aktuella objektet |

### Returvärde

En referens till sig själv

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)