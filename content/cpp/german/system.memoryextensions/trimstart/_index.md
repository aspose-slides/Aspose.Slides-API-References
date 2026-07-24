---
title: TrimStart()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das angegebene Element vom Anfang eines typisierten Spans.
type: docs
weight: 391
url: /de/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) function

Entfernt das angegebene Element vom Anfang eines typisierten Spans.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu kürzende Span |
| trimElement | const T\& | Das zu kürzende Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element vom Anfang entfernt wurde.

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) function

Entfernt das angegebene Element vom Anfang eines veränderbaren typisierten Spans.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der veränderbare Span, der gekürzt wird |
| trimElement | const T\& | Das zu kürzende Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element vom Anfang entfernt wurde.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Entfernt die angegebenen Elemente vom Anfang eines typisierten Spans.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu kürzende Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu kürzenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente vom Anfang entfernt wurden.

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Entfernt die angegebenen Elemente vom Anfang eines veränderbaren typisierten Spans.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der veränderbare Span, der gekürzt wird |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu kürzenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente vom Anfang entfernt wurden.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) function

Entfernt Leerzeichen vom Anfang eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu kürzende Zeichen-Span |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen vom Anfang entfernt wurden.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) function

Entfernt Leerzeichen vom Anfang eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der veränderbare Zeichen-Span, der gekürzt wird |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen vom Anfang entfernt wurden.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) function

Entfernt das angegebene Zeichen vom Anfang eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu kürzende Zeichen-Span |
| trimchar | char16_t | Das zu entfernende Zeichen |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Zeichen vom Anfang entfernt wurde.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) function

Entfernt das angegebene Zeichen vom Anfang eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der veränderbare Zeichen-Span, der gekürzt wird |
| trimchar | char16_t | Das zu entfernende Zeichen |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Zeichen vom Anfang entfernt wurde.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Entfernt die angegebenen Zeichen vom Anfang eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu kürzende Zeichen-Span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die zu entfernenden Zeichen |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Zeichen vom Anfang entfernt wurden.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Entfernt die angegebenen Zeichen vom Anfang eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der veränderbare Zeichen-Span, der gekürzt wird |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die zu entfernenden Zeichen |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Zeichen vom Anfang entfernt wurden.

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)