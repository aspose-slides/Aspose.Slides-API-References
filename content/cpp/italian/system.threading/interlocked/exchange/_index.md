---
title: Exchange()
second_title: Riferimento API di Aspose.Slides per C++
description: "Scambia il valore della variabile: memorizza il nuovo valore e restituisce il valore che la variabile aveva subito prima della memorizzazione."
type: docs
weight: 66
url: /it/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) metodo


Scambia il valore della variabile: memorizza il nuovo valore e restituisce il valore che la variabile aveva immediatamente prima della memorizzazione.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della variabile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location1 | T\& | Riferimento variabile da modificare. |
| value | T | Valore da memorizzare. |

### Valore restituito

Valore della variabile subito prima che fosse modificata.

## Interlocked::Exchange(T\&, T) metodo


Scambia il valore della variabile: memorizza il nuovo valore e restituisce il valore che la variabile aveva immediatamente prima della memorizzazione. Non implementato.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della variabile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location1 | T\& | Riferimento variabile da modificare. |
| value | T | Valore da memorizzare. |

### Valore restituito

Valore della variabile subito prima che fosse modificata.

## Vedi anche

* Classe [Interlocked](../)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)