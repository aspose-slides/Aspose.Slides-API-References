---
title: Trim()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het opgegeven element aan beide uiteinden van een getypte span.
type: docs
weight: 365
url: /nl/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) functie

Verwijdert het opgegeven element aan beide uiteinden van een getypte span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span die moet worden getrimd |
| trimElement | T | Het element dat moet worden getrimd |

### Retourwaarde

Een nieuwe span met het opgegeven element getrimd aan beide uiteinden

## System::MemoryExtensions::Trim(Span\<T\>\&, T) functie

Verwijdert het opgegeven element aan beide uiteinden van een wijzigbare getypte span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De wijzigbare span die moet worden getrimd |
| trimElement | T | Het element dat moet worden getrimd |

### Retourwaarde

Een nieuwe span met het opgegeven element getrimd aan beide uiteinden

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Verwijdert de opgegeven elementen aan beide uiteenden van een getypte span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span die moet worden getrimd |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De elementen die moeten worden getrimd |

### Retourwaarde

Een nieuwe span met de opgegeven elementen getrimd aan beide uiteinden

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Verwijdert de opgegeven elementen aan beide uiteinden van een wijzigbare getypte span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De wijzigbare span die moet worden getrimd |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De elementen die moeten worden getrimd |

### Retourwaarde

Een nieuwe span met de opgegeven elementen getrimd aan beide uiteinden

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) functie

Verwijdert witruimtekarakters aan beide uiteinden van een karakterspan.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakterspan die moet worden getrimd |

### Retourwaarde

Een nieuwe span met witruimte getrimd aan beide uiteinden

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) functie

Verwijdert witruimtekarakters aan beide uiteinden van een wijzigbare karakterspan.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De wijzigbare karakterspan die moet worden getrimd |

### Retourwaarde

Een nieuwe span met witruimte getrimd aan beide uiteinden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)