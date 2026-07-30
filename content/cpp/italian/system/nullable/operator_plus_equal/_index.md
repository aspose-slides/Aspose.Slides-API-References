---
title: operator+=()
second_title: Riferimento API Aspose.Slides per C++
description: Reimposta l'oggetto corrente in modo che rappresenti un valore nullo.
type: docs
weight: 235
url: /it/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metodo

Reimposta l'oggetto corrente in modo che rappresenti un valore nullo.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Valore di ritorno

Una copia dell'oggetto

## Nullable::operator+=(const T1\&) metodo

Applica [operator+=()](./) al valore rappresentato dall'oggetto corrente usando il valore specificato come argomento a destra.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del valore utilizzato come valore a destra di [operator+=()](./) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | Un riferimento costante al valore che è usato come valore a destra del [operator+=()](./) applicato al valore rappresentato dall'oggetto corrente. |

### Valore di ritorno

Un riferimento all'oggetto

## Nullable::operator+=(const Nullable\<T1\>\&) metodo

Applica [operator+=()](./) al valore rappresentato dall'oggetto corrente usando il valore rappresentato dall'oggetto [Nullable](../) specificato come argomento a destra.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo sottostante di un oggetto [Nullable](../) il cui valore rappresentato è utilizzato come argomento a destra di [operator+=()](./) |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Un riferimento costante all'oggetto [Nullable](../) il cui valore rappresentato è usato come argomento a destra del [operator+=()](./) applicato al valore rappresentato dall'oggetto corrente. |

### Valore di ritorno

Un riferimento all'oggetto

## Vedi anche

* Classe [Nullable](../)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)