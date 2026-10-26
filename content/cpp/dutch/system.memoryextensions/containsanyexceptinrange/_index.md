---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een alleen-lezen span een element buiten het opgegeven bereik bevat.
type: docs
weight: 79
url: /nl/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie

Controleert of een alleen-lezen span een element buiten het opgegeven bereik bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span (moet vergelijkbaar zijn) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| lowInclusive | const T\& | De ondergrens (inclusief) |
| highInclusive | const T\& | De bovengrens (inclusief) |

### Retourwaarde

true if any element outside the range is found, false otherwise

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) functie

Controleert of een wijzigbare span een element buiten het opgegeven bereik bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span (moet vergelijkbaar zijn) |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De wijzigbare span waarin gezocht wordt |
| lowInclusive | const T\& | De ondergrens (inclusief) |
| highInclusive | const T\& | De bovengrens (inclusief) |

### Retourwaarde

true if any element outside the range is found, false otherwise

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)