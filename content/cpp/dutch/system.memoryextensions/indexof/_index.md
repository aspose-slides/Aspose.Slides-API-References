---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referentie
description: Zoekt de index van een ReadOnlySpan<T>-waarde in een andere ReadOnlySpan<T>
type: docs
weight: 144
url: /nl/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Zoekt de index van een ReadOnlySpan<T>-waarde in een andere ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarnaar gezocht wordt |

### Retourwaarde

De nulgebaseerde index van de eerste vondst, of -1 indien niet gevonden

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) functie


Zoekt de index van een enkele waarde in een ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value | const T\& | De waarde waarnaar gezocht wordt |

### Retourwaarde

De nulgebaseerde index van de eerste vondst, of -1 indien niet gevonden

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Zoekt de index van een ReadOnlySpan<T>-waarde in een Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht wordt |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarnaar gezocht wordt |

### Retourwaarde

De nulgebaseerde index van de eerste vondst, of -1 indien niet gevonden

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) functie


Zoekt de index van een enkele waarde in een Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht wordt |
| value | const T\& | De waarde waarnaar gezocht wordt |

### Retourwaarde

De nulgebaseerde index van de eerste vondst, of -1 indien niet gevonden

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie


Zoekt de index van een ReadOnlySpan<char16_t>-waarde in een ReadOnlySpan<char16_t> met StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De span waarin gezocht wordt |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De waarde waarnaar gezocht wordt |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het stringvergelijkingstype om te gebruiken |

### Retourwaarde

De nulgebaseerde index van de eerste vondst, of -1 indien niet gevonden

## Zie ook

* Enumeratie [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)