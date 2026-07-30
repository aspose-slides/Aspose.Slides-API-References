---
title: TrimEnd()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'elemento specificato dalla fine di uno span tipizzato.
type: docs
weight: 378
url: /it/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function

Rimuove l'elemento specificato dalla fine di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da ridurre |
| trimElement | const T\& | L'elemento da ridurre |

### Valore restituito

Un nuovo span con l'elemento specificato rimosso dalla fine

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function

Rimuove l'elemento specificato dalla fine di uno span tipizzato modificabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span modificabile da ridurre |
| trimElement | const T\& | L'elemento da ridurre |

### Valore restituito

Un nuovo span con l'elemento specificato rimosso dalla fine

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Rimuove gli elementi specificati dalla fine di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da ridurre |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da ridurre |

### Valore restituito

Un nuovo span con gli elementi specificati rimossi dalla fine

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Rimuove gli elementi specificati dalla fine di uno span tipizzato modificabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span modificabile da ridurre |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da ridurre |

### Valore restituito

Un nuovo span con gli elementi specificati rimossi dalla fine

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function

Rimuove i caratteri di spaziatura dalla fine di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da ridurre |

### Valore restituito

Un nuovo span con gli spazi bianchi rimossi dalla fine

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function

Rimuove i caratteri di spaziatura dalla fine di uno span di caratteri modificabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri modificabile da ridurre |

### Valore restituito

Un nuovo span con gli spazi bianchi rimossi dalla fine

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function

Rimuove il carattere specificato dalla fine di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da ridurre |
| trimchar | char16_t | Il carattere da ridurre |

### Valore restituito

Un nuovo span con il carattere specificato rimosso dalla fine

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function

Rimuove il carattere specificato dalla fine di uno span di caratteri modificabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri modificabile da ridurre |
| trimchar | char16_t | Il carattere da ridurre |

### Valore restituito

Un nuovo span con il carattere specificato rimosso dalla fine

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Rimuove i caratteri specificati dalla fine di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da ridurre |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | I caratteri da ridurre |

### Valore restituito

Un nuovo span con i caratteri specificati rimossi dalla fine

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Rimuove i caratteri specificati dalla fine di uno span di caratteri modificabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri modificabile da ridurre |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | I caratteri da ridurre |

### Valore restituito

Un nuovo span con i caratteri specificati rimossi dalla fine

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)