---
title: Trim()
second_title: Aspose.Slides für C++ API-Referenz
description: Schneidet das angegebene Element von beiden Enden eines typisierten Spans ab.
type: docs
weight: 365
url: /de/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) Funktion

Schneidet das angegebene Element von beiden Enden eines typisierten Spans ab.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu trimmbende Span |
| trimElement | T | Das zu trimmbende Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element von beiden Enden abgeschnitten wurde

## System::MemoryExtensions::Trim(Span\<T\>\&, T) Funktion

Schneidet das angegebene Element von beiden Enden eines veränderbaren typisierten Spans ab.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der veränderbare Span, der getrimmt werden soll |
| trimElement | T | Das zu trimmbende Element |

### Rückgabewert

Ein neuer Span, bei dem das angegebene Element von beiden Enden abgeschnitten wurde

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Schneidet die angegebenen Elemente von beiden Enden eines typisierten Spans ab.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu trimmbende Span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu trimmenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente von beiden Enden abgeschnitten wurden

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Schneidet die angegebenen Elemente von beiden Enden eines veränderbaren typisierten Spans ab.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Der veränderbare Span, der getrimmt werden soll |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu trimmenden Elemente |

### Rückgabewert

Ein neuer Span, bei dem die angegebenen Elemente von beiden Enden abgeschnitten wurden

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) Funktion

Schneidet Leerzeichenzeichen von beiden Enden eines Zeichen-Spans ab.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu trimmbende Zeichen-Span |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen von beiden Enden entfernt wurden

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) Funktion

Schneidet Leerzeichenzeichen von beiden Enden eines veränderbaren Zeichen-Spans ab.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Der veränderbare Zeichen-Span, der getrimmt werden soll |

### Rückgabewert

Ein neuer Span, bei dem Leerzeichen von beiden Enden entfernt wurden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)