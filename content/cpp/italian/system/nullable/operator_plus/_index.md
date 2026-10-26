---
title: operator+()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un'istanza di Nullable<T> creata con il costruttore predefinito.
type: docs
weight: 209
url: /it/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const metodo

Restituisce un'istanza di Nullable<T> creata con il costruttore predefinito.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const metodo

Somma valori nullable e non nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando destro. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | valore da aggiungere. |

### Valore restituito

Risultato della somma.

## Nullable::operator+(const Nullable\<T1\>\&) const metodo

Somma valori nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando destro. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valore da aggiungere. |

### Valore restituito

Risultato della somma.

## Vedi anche

* Classe [Nullable](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)