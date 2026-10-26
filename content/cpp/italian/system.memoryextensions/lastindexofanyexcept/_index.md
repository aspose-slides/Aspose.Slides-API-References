---
title: LastIndexOfAnyExcept()
second_title: Riferimento API Aspose.Slides per C++
description: Trova l'ultima occorrenza di qualsiasi elemento tranne tre valori specificati all'interno di uno span.
type: docs
weight: 235
url: /it/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne tre valori specificati all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span su cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |
| value2 | const T\& | Il terzo valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne tre valori specificati all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span su cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |
| value2 | const T\& | Il terzo valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne due valori specificati all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span su cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne due valori specificati all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span su cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne un valore specificato all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span su cui cercare |
| value | const T\& | Il valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne un valore specificato all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span su cui cercare |
| value | const T\& | Il valore da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne i valori di una sequenza all'interno di uno span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span su cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza di valori da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne i valori di una sequenza all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span su cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La sequenza di valori da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) funzione

Trova l'ultima occorrenza di qualsiasi elemento tranne i valori di una sequenza modificabile all'interno di uno span modificabile.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi nello span |

### Parametri

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span su cui cercare |
| values | const [Span](../../system/span/)\<T\>\& | La sequenza di valori da escludere |

### Valore di ritorno

L'indice basato su zero dell'ultimo elemento non escluso, oppure -1 se non trovato

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)