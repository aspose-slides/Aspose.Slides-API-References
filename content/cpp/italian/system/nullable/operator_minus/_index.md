---
title: operator-()
second_title: Riferimento API di Aspose.Slides per C++
description: Sottrae valori nullable e puntati a null.
type: docs
weight: 222
url: /it/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metodo

Sottrae valori nullable e puntati a null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando destro, dovrebbe essere nullptr_t. |

### Valore di ritorno

Oggetto [Nullable](../) vuoto.

## Nullable::operator-(const T1&) const metodo

Sottrae valori nullable e non nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando destro. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const T1\& | valore da sottrarre. |

### Valore di ritorno

Risultato della sottrazione.

## Nullable::operator-(const Nullable\<T1\>\&) const metodo

Sottrae valori nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando destro. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valore da sottrarre. |

### Valore di ritorno

Risultato della sottrazione.

## Vedi anche

* Classe [Nullable](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)