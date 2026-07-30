---
title: ContainsAnyExcept()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se uno span di sola lettura contiene qualche elemento diverso da tre valori specificati.
type: docs
weight: 66
url: /it/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funzione


Verifica se uno span di sola lettura contiene qualche elemento diverso da tre valori specificati.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |
| value2 | const T\& | Il terzo valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dai valori specificati, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funzione


Verifica se uno span modificabile contiene qualche elemento diverso da tre valori specificati.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |
| value2 | const T\& | Il terzo valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dai valori specificati, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funzione


Verifica se uno span di sola lettura contiene qualche elemento diverso da due valori specificati.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dai valori specificati, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) funzione


Verifica se uno span modificabile contiene qualche elemento diverso da due valori specificati.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| value0 | const T\& | Il primo valore da escludere |
| value1 | const T\& | Il secondo valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dai valori specificati, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funzione


Verifica se uno span di sola lettura contiene qualche elemento diverso da un valore specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| value | const T\& | Il valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dal valore specificato, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) funzione


Verifica se uno span modificabile contiene qualche elemento diverso da un valore specificato.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| value | const T\& | Il valore da escludere |

### Valore restituito

true se viene trovato un elemento diverso dal valore specificato, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Verifica se uno span di sola lettura contiene qualche elemento diverso da quelli in un altro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di valori da escludere |

### Valore restituito

true se viene trovato un elemento non presente in values, false altrimenti

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione


Verifica se uno span modificabile contiene qualche elemento diverso da quelli in uno span di sola lettura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi negli span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Lo span modificabile in cui cercare |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span di sola lettura di valori da escludere |

### Valore restituito

true se viene trovato un elemento non presente in values, false altrimenti

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)