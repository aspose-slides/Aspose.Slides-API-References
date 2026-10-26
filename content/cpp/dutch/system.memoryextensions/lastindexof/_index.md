---
title: LastIndexOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt de laatste verschijning van een reeks binnen een span.
type: docs
weight: 209
url: /nl/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Zoekt de laatste verschijning van een reeks binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De reeks om te zoeken |

### Retourwaarde

De nulgebaseerde index van de laatste verschijning, of -1 als deze niet gevonden is

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) functie

Zoekt de laatste verschijning van een enkele waarde binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| value | const T\& | De waarde om te zoeken |

### Retourwaarde

De nulgebaseerde index van de laatste verschijning, of -1 als deze niet gevonden is

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Zoekt de laatste verschijning van een reeks binnen een veranderbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De reeks om te zoeken |

### Retourwaarde

De nulgebaseerde index van de laatste verschijning, of -1 als deze niet gevonden is

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) functie

Zoekt de laatste verschijning van een enkele waarde binnen een veranderbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| value | const T\& | De waarde om te zoeken |

### Retourwaarde

De nulgebaseerde index van de laatste verschijning, of -1 als deze niet gevonden is

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie

Zoekt de laatste verschijning van een waarde binnen een span met een opgegeven tekenreeksvergelijking.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De span waarin gezocht moet worden |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De waarde om te zoeken |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het type stringvergelijking dat moet worden uitgevoerd |

### Retourwaarde

De nulgebaseerde index van de laatste verschijning, of -1 als deze niet gevonden is

## Zie ook

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)