---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt de laatste verschijning van een element binnen het opgegeven bereik in een span.
type: docs
weight: 261
url: /nl/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Zoekt de laatste verschijning van een element binnen het opgegeven bereik in een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| lowInclusive | const T\& | De ondergrens van het bereik (inclusief) |
| highInclusive | const T\& | De bovengrens van het bereik (inclusief) |

### Retourwaarde

De nul-gebaseerde index van het laatste element binnen het bereik, of -1 als niet gevonden

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Zoekt de laatste verschijning van een element binnen het opgegeven bereik in een mutabele span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht wordt |
| lowInclusive | const T\& | De ondergrens van het bereik (inclusief) |
| highInclusive | const T\& | De bovengrens van het bereik (inclusief) |

### Retourwaarde

De nul-gebaseerde index van het laatste element binnen het bereik, of -1 als niet gevonden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)