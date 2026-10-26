---
title: TrimEnd()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt das angegebene Element vom Ende eines typisierten Spans.
type: docs
weight: 378
url: /de/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Entfernt das angegebene Element vom Ende eines typisierten Spans.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu trimmbare Span |
| trimElement | const T\& | Das zu trimmbare Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element vom Ende entfernt wurde

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) Funktion

Entfernt das angegebene Element vom Ende eines veränderbaren typisierten Spans.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der zu trimmbare veränderbare Span |
| trimElement | const T\& | Das zu trimmbare Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element vom Ende entfernt wurde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Entfernt die angegebenen Elemente vom Ende eines typisierten Spans.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu trimmbare Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu trimmenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente vom Ende entfernt wurden

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Entfernt die angegebenen Elemente vom Ende eines veränderbaren typisierten Spans.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der zu trimmbare veränderbare Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu trimmenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente vom Ende entfernt wurden

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) Funktion

Entfernt Leerzeichenzeichen vom Ende eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu trimmbare Zeichen-Span |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen vom Ende entfernt wurden

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) Funktion

Entfernt Leerzeichenzeichen vom Ende eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der zu trimmbare veränderbare Zeichen-Span |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen vom Ende entfernt wurden

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) Funktion

Entfernt das angegebene Zeichen vom Ende eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu trimmbare Zeichen-Span |
| trimchar | char16_t | Das zu trimmbare Zeichen |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Zeichen vom Ende entfernt wurde

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) Funktion

Entfernt das angegebene Zeichen vom Ende eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der zu trimmbare veränderbare Zeichen-Span |
| trimchar | char16_t | Das zu trimmbare Zeichen |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Zeichen vom Ende entfernt wurde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) Funktion

Entfernt die angegebenen Zeichen vom Ende eines Zeichen-Spans.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu trimmbare Zeichen-Span |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die zu trimmenden Zeichen |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Zeichen vom Ende entfernt wurden

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) Funktion

Entfernt die angegebenen Zeichen vom Ende eines veränderbaren Zeichen-Spans.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der zu trimmbare veränderbare Zeichen-Span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Die zu trimmenden Zeichen |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Zeichen vom Ende entfernt wurden

## Sie Sie Auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)