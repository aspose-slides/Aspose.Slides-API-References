---
title: IndexOfAnyInRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt de index van het eerste element dat zich binnen het opgegeven bereik bevindt in een ReadOnlySpan<T>
type: docs
weight: 196
url: /nl/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie

Zoekt de index van het eerste element dat zich binnen het gespecificeerde bereik bevindt in een ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

De nulgebaseerde index van het eerste element binnen het bereik, of -1 als niet gevonden

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) functie


Zoekt de index van het eerste element dat zich binnen het gespecificeerde bereik bevindt in een Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
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

De nulgebaseerde index van het eerste element binnen het bereik, of -1 als niet gevonden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)