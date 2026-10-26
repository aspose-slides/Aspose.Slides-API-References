---
title: LastIndexOfAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt het laatste voorkomen van een van drie opgegeven waarden binnen een span.
type: docs
weight: 222
url: /nl/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van een van drie opgegeven waarden binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |
| value2 | const T\& | De derde waarde om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van een van drie opgegeven waarden binnen een wijzigbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |
| value2 | const T\& | De derde waarde om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van een van twee opgegeven waarden binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van een van twee opgegeven waarden binnen een wijzigbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Zoekt het laatste voorkomen van een willekeurige waarde uit een reeks binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De reeks waarden om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Zoekt het laatste voorkomen van een willekeurige waarde uit een reeks binnen een wijzigbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De reeks waarden om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) functie

Zoekt het laatste voorkomen van een willekeurige waarde uit een wijzigbare reeks binnen een wijzigbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| values | const [Span](../../system/span/)\<T\>\& | De reeks waarden om naar te zoeken |

### Retourwaarde

De nulgebaseerde index van het laatste voorkomen, of -1 indien niet gevonden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)