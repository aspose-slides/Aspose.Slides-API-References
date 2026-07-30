---
title: LastIndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca l'oggetto specificato e restituisce l'indice a base zero dell'ultima occorrenza nell'intera lista.
type: docs
weight: 469
url: /it/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metodo

Cerca l'oggetto specificato e restituisce l'indice a base zero dell'ultima occorrenza all'interno dell'intera lista.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | L'oggetto da localizzare nella lista |

### Valore di ritorno

L'indice a base zero dell'ultima occorrenza dell'elemento all'interno dell'intero [List](../), se trovato; altrimenti, -1.

## List::LastIndexOf(const T\&, int32_t) const metodo

Cerca l'oggetto specificato e restituisce l'indice a base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nel [List](../) che si estende dal primo elemento all'indice specificato.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | L'oggetto da localizzare nella lista |
| index | **int32_t** | L'indice a base zero di partenza della ricerca all'indietro. |

### Valore di ritorno

L'indice a base zero dell'ultima occorrenza dell'elemento all'interno dell'intervallo di elementi nel [List](../) che si estende dal primo elemento all'indice, se trovato; altrimenti, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metodo

Cerca l'oggetto specificato e restituisce l'indice a base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nel [List](../) che contiene il numero specificato di elementi e termina all'indice specificato.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const T\& | L'oggetto da localizzare nel [List](../) |
| index | **int32_t** | L'indice a base zero di partenza della ricerca all'indietro. |
| count | **int32_t** | Il numero di elementi nella sezione da cercare. |

### Valore di ritorno

L'indice a base zero dell'ultima occorrenza dell'elemento all'interno dell'intervallo di elementi nel [List](../) che contiene count elementi e termina all'indice, se trovato; altrimenti, -1.

## Vedi anche

* Classe [List](../)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)