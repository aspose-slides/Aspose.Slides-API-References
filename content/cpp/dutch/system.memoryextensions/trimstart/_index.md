---
title: TrimStart()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het gespecificeerde element vanaf het begin van een getypeerde span.
type: docs
weight: 391
url: /nl/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) functie

Verwijdert het gespecificeerde element vanaf het begin van een getypeerde span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | const T\& | The element to trim |

### Retourwaarde

Een nieuwe span met het gespecificeerde element verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) functie

Verwijdert het gespecificeerde element vanaf het begin van een mutabele getypeerde span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | const T\& | The element to trim |

### Retourwaarde

Een nieuwe span met het gespecificeerde element verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Verwijdert de gespecificeerde elementen vanaf het begin van een getypeerde span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Retourwaarde

Een nieuwe span met de gespecificeerde elementen verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Verwijdert de gespecificeerde elementen vanaf het begin van een mutabele getypeerde span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### Retourwaarde

Een nieuwe span met de gespecificeerde elementen verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) functie

Verwijdert witruimtekarakters vanaf het begin van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |

### Retourwaarde

Een nieuwe span met witruimte verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) functie

Verwijdert witruimtekarakters vanaf het begin van een mutabele karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De mutabele karakter-span om te trimmen |

### Retourwaarde

Een nieuwe span met witruimte verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) functie

Verwijdert het opgegeven teken vanaf het begin van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |
| trimchar | char16_t | Het te trimmen teken |

### Retourwaarde

Een nieuwe span met het opgegeven teken verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) functie

Verwijdert het opgegeven teken vanaf het begin van een mutabele karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De mutabele karakter-span om te trimmen |
| trimchar | char16_t | Het te trimmen teken |

### Retourwaarde

Een nieuwe span met het opgegeven teken verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) functie

Verwijdert de opgegeven karakters vanaf het begin van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De te trimmen karakters |

### Retourwaarde

Een nieuwe span met de opgegeven karakters verwijderd vanaf het begin

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) functie

Verwijdert de opgegeven karakters vanaf het begin van een mutabele karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De mutabele karakter-span om te trimmen |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De te trimmen karakters |

### Retourwaarde

Een nieuwe span met de opgegeven karakters verwijderd vanaf het begin

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)