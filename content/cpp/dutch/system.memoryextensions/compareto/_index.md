---
title: CompareTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee tekenreeksen met de gespecificeerde regels voor tekenreeksvergelijking.
type: docs
weight: 404
url: /nl/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie

Vergelijkt twee tekenreeksen met de gespecificeerde regels voor tekenreeksvergelijking.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De eerste tekenreeks |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De tweede tekenreeks |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het type tekenreeksvergelijking dat moet worden uitgevoerd |

### Retourwaarde

Negatieve waarde als span < other, nul als gelijk, positieve waarde als span > other

## Zie ook

* Enumeratie [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)