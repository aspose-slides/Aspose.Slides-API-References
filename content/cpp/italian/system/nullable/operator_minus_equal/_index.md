---
title: operator-=()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce un'istanza della classe Nullable che rappresenta un valore nullo.
type: docs
weight: 248
url: /it/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metodo

Restituisce un'istanza della classe [Nullable](../) che rappresenta un valore nullo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metodo

Applica [operator-=()](./) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore usato come valore a destra di [operator-=()](./) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante al valore che è usato come valore a destra del [operator-=()](./) applicato al valore rappresentato dall'oggetto corrente. |

### Valore restituito

Un riferimento a se stesso

## Nullable::operator-=(const Nullable\<T1\>\&) metodo

Applica [operator-=()](./) al valore rappresentato dall'oggetto corrente usando il valore rappresentato dal specificato oggetto [Nullable](../) come argomento a destra.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo sottostante di un oggetto [Nullable](../) il cui valore rappresentato è usato come argomento a destra di [operator-=()](./) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) il cui valore rappresentato è usato come argomento a destra del [operator-=()](./) applicato al valore rappresentato dall'oggetto corrente. |

### Valore restituito

Un riferimento a se stesso

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)