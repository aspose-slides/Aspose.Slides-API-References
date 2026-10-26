---
title: CompareExchange()
second_title: Riferimento API di Aspose.Slides per C++
description: "Scambia il valore della variabile: verifica se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso."
type: docs
weight: 79
url: /it/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) metodo

Scambia il valore della variabile: verifica se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della variabile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location1 | T\& | Riferimento alla variabile da modificare. |
| value | T | Valore da memorizzare. |
| comparand | T | Valore con cui confrontare il valore della variabile prima dello scambio. |

### Valore di ritorno

Valore della variabile all’inizio dell’operazione, indipendentemente dal fatto che sia stato modificato o meno.

## Interlocked::CompareExchange(T\&, T, T) metodo

Scambia il valore della variabile: verifica se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso. Non implementato.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo della variabile. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location1 | T\& | Riferimento alla variabile da modificare. |
| value | T | Valore da memorizzare. |
| comparand | T | Valore con cui confrontare il valore della variabile prima dello scambio. |

### Valore di ritorno

Valore della variabile all’inizio dell’operazione, indipendentemente dal fatto che sia stato modificato o meno.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) metodo

Scambia il valore della variabile: verifica se la variabile è uguale a un valore specifico e memorizza il nuovo valore solo se il valore memorizzato corrisponde a quello atteso.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| location1 | **int32_t**\& | Riferimento alla variabile da modificare. |
| value | **int32_t** | Valore da memorizzare. |
| comparand | **int32_t** | Valore con cui confrontare il valore della variabile prima dello scambio. |
| succeeded | **bool**\& | Riferimento a variabile impostata a true se lo scambio è avvenuto e a false altrimenti. |

### Valore di ritorno

Valore della variabile all’inizio dell’operazione, indipendentemente dal fatto che sia stato modificato o meno.

## Vedi anche

* Classe [Interlocked](../)
* Namespace [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)