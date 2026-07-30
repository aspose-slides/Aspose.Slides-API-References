---
title: LastIndexOfAny()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova l'ultima occorrenza di uno dei tre valori specificati all'interno di uno span.
type: docs
weight: 222
url: /it/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di uno dei tre valori specificati all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |
| value2 | const T\& | Il terzo valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di uno dei tre valori specificati all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |
| value2 | const T\& | Il terzo valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di uno dei due valori specificati all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) funzione


Trova l'ultima occorrenza di uno dei due valori specificati all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da cercare |
| value1 | const T\& | Il secondo valore da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Trova l'ultima occorrenza di qualsiasi valore di una sequenza all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza di valori da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Trova l'ultima occorrenza di qualsiasi valore di una sequenza all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza di valori da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) funzione


Trova l'ultima occorrenza di qualsiasi valore di una sequenza modificabile all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span in cui cercare |
| values | const [Span](../../system/span/)\<T\>\& | La sequenza di valori da cercare |

### Valore di ritorno

L'indice basato su zero dell'ultima occorrenza, o -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)