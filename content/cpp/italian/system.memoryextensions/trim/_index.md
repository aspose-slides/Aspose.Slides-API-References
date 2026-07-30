---
title: Trim()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'elemento specificato da entrambe le estremità di uno span tipizzato.
type: docs
weight: 365
url: /it/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function

Rimuove l'elemento specificato da entrambe le estremità di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da ritagliare |
| trimElement | T | L'elemento da ritagliare |

### Valore restituito

Uno span nuovo con l'elemento specificato rimosso da entrambe le estremità

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function

Rimuove l'elemento specificato da entrambe le estremità di uno span tipizzato mutabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span mutabile da ritagliare |
| trimElement | T | L'elemento da ritagliare |

### Valore restituito

Uno span nuovo con l'elemento specificato rimosso da entrambe le estremità

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Rimuove gli elementi specificati da entrambe le estremità di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da ritagliare |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da ritagliare |

### Valore restituito

Uno span nuovo con gli elementi specificati rimossi da entrambe le estremità

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Rimuove gli elementi specificati da entrambe le estremità di uno span tipizzato mutabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span mutabile da ritagliare |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da ritagliare |

### Valore restituito

Uno span nuovo con gli elementi specificati rimossi da entrambe le estremità

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function

Rimuove i caratteri di spaziatura bianca da entrambe le estremità di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da ritagliare |

### Valore restituito

Uno span nuovo con gli spazi bianchi rimossi da entrambe le estremità

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function

Rimuove i caratteri di spaziatura bianca da entrambe le estremità di uno span di caratteri mutabile.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri mutabile da ritagliare |

### Valore restituito

Uno span nuovo con gli spazi bianchi rimossi da entrambe le estremità

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)