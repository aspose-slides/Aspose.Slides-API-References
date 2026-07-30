---
title: TrimStart()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove l'elemento specificato dall'inizio di uno span tipizzato.
type: docs
weight: 391
url: /it/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) funzione

Rimuove l'elemento specificato dall'inizio di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da rimuovere |
| trimElement | const T\& | L'elemento da rimuovere |

### Valore di ritorno

Un nuovo span con l'elemento specificato rimosso dall'inizio

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) funzione

Rimuove l'elemento specificato dall'inizio di uno span tipizzato mutabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span mutabile da rimuovere |
| trimElement | const T\& | L'elemento da rimuovere |

### Valore di ritorno

Un nuovo span con l'elemento specificato rimosso dall'inizio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Rimuove gli elementi specificati dall'inizio di uno span tipizzato.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Lo span da rimuovere |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da rimuovere |

### Valore di ritorno

Un nuovo span con gli elementi specificati rimossi dall'inizio

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Rimuove gli elementi specificati dall'inizio di uno span tipizzato mutabile.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di elementi nello span |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Lo span mutabile da rimuovere |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Gli elementi da rimuovere |

### Valore di ritorno

Un nuovo span con gli elementi specificati rimossi dall'inizio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) funzione

Rimuove i caratteri di spaziatura dall'inizio di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da rimuovere |

### Valore di ritorno

Un nuovo span con i caratteri di spaziatura rimossi dall'inizio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) funzione

Rimuove i caratteri di spaziatura dall'inizio di uno span di caratteri mutabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri mutabile da rimuovere |

### Valore di ritorno

Un nuovo span con i caratteri di spaziatura rimossi dall'inizio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) funzione

Rimuove il carattere specificato dall'inizio di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da rimuovere |
| trimchar | char16_t | Il carattere da rimuovere |

### Valore di ritorno

Un nuovo span con il carattere specificato rimosso dall'inizio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) funzione

Rimuove il carattere specificato dall'inizio di uno span di caratteri mutabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri mutabile da rimuovere |
| trimchar | char16_t | Il carattere da rimuovere |

### Valore di ritorno

Un nuovo span con il carattere specificato rimosso dall'inizio

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funzione

Rimuove i caratteri specificati dall'inizio di uno span di caratteri.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Lo span di caratteri da rimuovere |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | I caratteri da rimuovere |

### Valore di ritorno

Un nuovo span con i caratteri specificati rimossi dall'inizio

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) funzione

Rimuove i caratteri specificati dall'inizio di uno span di caratteri mutabile.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Lo span di caratteri mutabile da rimuovere |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | I caratteri da rimuovere |

### Valore di ritorno

Un nuovo span con i caratteri specificati rimossi dall'inizio

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Spazio dei nomi [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)