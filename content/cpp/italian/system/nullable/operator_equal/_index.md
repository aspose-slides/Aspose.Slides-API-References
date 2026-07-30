---
title: operator=()
second_title: Riferimento API Aspose.Slides per C++
description: Assegna null all'oggetto corrente.
type: docs
weight: 14
url: /it/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metodo

Assegna null all'oggetto corrente.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Valore di ritorno

Un oggetto [Nullable](../) che rappresenta un valore null.

## Nullable::operator=(const T1\&) metodo

Sostituisce il valore attualmente rappresentato dall'oggetto con quello specificato.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Il | tipo del nuovo valore da rappresentare nell'oggetto corrente |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const T1\& | Il nuovo valore da rappresentare nell'oggetto corrente |

### Valore di ritorno

Un riferimento a se stesso

## Nullable::operator=(const Nullable\<T1\>\&) metodo

Sostituisce il valore attualmente rappresentato dall'oggetto con quello specificato.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Il | tipo del nuovo valore da rappresentare nell'oggetto corrente |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Il nuovo valore da rappresentare nell'oggetto corrente |

### Valore di ritorno

Un riferimento a se stesso

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)