---
title: ContainsAnyInRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een read-only span een element bevat binnen het opgegeven bereik.
type: docs
weight: 92
url: /nl/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie


Controleert of een read-only span een element bevat binnen het opgegeven bereik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type elementen in de span (moet vergelijkbaar zijn) |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span om in te zoeken |
| lowInclusive | const T\& | De onderste grens (inclusief) |
| highInclusive | const T\& | De bovenste grens (inclusief) |

### Retourwaarde

true als een element binnen het bereik wordt gevonden, false anders

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) functie


Controleert of een mutable span een element bevat binnen het opgegeven bereik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type elementen in de span (moet vergelijkbaar zijn) |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span om in te zoeken |
| lowInclusive | const T\& | De onderste grens (inclusief) |
| highInclusive | const T\& | De bovenste grens (inclusief) |

### Retourwaarde

true als een element binnen het bereik wordt gevonden, false anders

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)