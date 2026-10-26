---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt het laatste voorkomen van elk element buiten het opgegeven bereik binnen een span.
type: docs
weight: 248
url: /nl/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van elk element buiten het opgegeven bereik binnen een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| lowInclusive | const T\& | De ondergrens van het bereik (inclusief) |
| highInclusive | const T\& | De bovengrens van het bereik (inclusief) |

### Retourwaarde

De nulgebaseerde index van het laatste element buiten het bereik, of -1 indien niet gevonden

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) functie

Zoekt het laatste voorkomen van elk element buiten het opgegeven bereik binnen een aanpasbare span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht moet worden |
| lowInclusive | const T\& | De ondergrens van het bereik (inclusief) |
| highInclusive | const T\& | De bovengrens van het bereik (inclusief) |

### Retourwaarde

De nulgebaseerde index van het laatste element buiten het bereik, of -1 indien niet gevonden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)