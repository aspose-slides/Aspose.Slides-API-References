---
title: TrimEnd()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het opgegeven element van het einde van een getypeerde span.
type: docs
weight: 378
url: /nl/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) function


Verwijdert het opgegeven element van het einde van een getypeerde span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te trimmen |
| trimElement | const T\& | Het element om te trimmen |

### Retourwaarde

Een nieuwe span met het opgegeven element getrimd van het einde

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) function


Verwijdert het opgegeven element van het einde van een wijzigbare getypeerde span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De wijzigbare span om te trimmen |
| trimElement | const T\& | Het element om te trimmen |

### Retourwaarde

Een nieuwe span met het opgegeven element getrimd van het einde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Verwijdert de opgegeven elementen van het einde van een getypeerde span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om te trimmen |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De elementen om te trimmen |

### Retourwaarde

Een nieuwe span met de opgegeven elementen getrimd van het einde

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Verwijdert de opgegeven elementen van het einde van een wijzigbare getypeerde span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De wijzigbare span om te trimmen |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De elementen om te trimmen |

### Retourwaarde

Een nieuwe span met de opgegeven elementen getrimd van het einde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) function


Verwijdert witruimte-tekens van het einde van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |

### Retourwaarde

Een nieuwe span met witruimte getrimd van het einde

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) function


Verwijdert witruimte-tekens van het einde van een wijzigbare karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De wijzigbare karakter-span om te trimmen |

### Retourwaarde

Een nieuwe span met witruimte getrimd van het einde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) function


Verwijdert het opgegeven teken van het einde van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |
| trimchar | char16_t | Het teken om te trimmen |

### Retourwaarde

Een nieuwe span met het opgegeven teken getrimd van het einde

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) function


Verwijdert het opgegeven teken van het einde van een wijzigbare karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De wijzigbare karakter-span om te trimmen |
| trimchar | char16_t | Het teken om te trimmen |

### Retourwaarde

Een nieuwe span met het opgegeven teken getrimd van het einde

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function


Verwijdert de opgegeven tekens van het einde van een karakter-span.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De karakter-span om te trimmen |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De tekens om te trimmen |

### Retourwaarde

Een nieuwe span met de opgegeven tekens getrimd van het einde

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function


Verwijdert de opgegeven tekens van het einde van een wijzigbare karakter-span.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | De wijzigbare karakter-span om te trimmen |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De tekens om te trimmen |

### Retourwaarde

Een nieuwe span met de opgegeven tekens getrimd van het einde

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)