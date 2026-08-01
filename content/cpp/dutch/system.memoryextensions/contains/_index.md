---
title: Contains()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een read-only span een specifieke waarde bevat.
type: docs
weight: 40
url: /nl/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) functie

Controleert of een read-only span een specifieke waarde bevat.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht moet worden |
| value | const T\& | De te zoeken waarde |

### Retourwaarde

true als waarde wordt gevonden in de span, false anders

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) functie

Controleert of een mutable span een specifieke waarde bevat.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De mutable span waarin gezocht moet worden |
| value | const T\& | De te zoeken waarde |

### Retourwaarde

true als waarde wordt gevonden in de span, false anders

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) functie

Controleert of een character span een andere character span bevat met opgegeven vergelijkingsregels.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De span waarin gezocht moet worden |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De te zoeken span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Het type stringvergelijking dat moet worden uitgevoerd |

### Retourwaarde

true als waarde wordt gevonden in de span, false anders

## Zie ook

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)