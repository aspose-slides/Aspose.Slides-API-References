---
title: AsSpan()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een span van een array.
type: docs
weight: 1
url: /nl/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) functie

Maakt een span van een array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de array. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | De bron-array. |
| start | **int32_t** | De startindex in de array. |
| length | **int32_t** | De lengte van de span. |

### Retourwaarde

Span<T> die het opgegeven gedeelte van de array beslaat.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) functie

Maakt een alleen-lezen span van een string.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | De bron-string. |
| start | **int32_t** | De startindex in de string. |
| length | **int32_t** | De lengte van de span. |

### Retourwaarde

ReadOnlySpan<char16_t> die het opgegeven gedeelte van de string beslaat.

## Zie ook

* Typedef [ArrayPtr](../../system/arrayptr/)
* Klasse [Span](../../system/span/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [String](../../system/string/)
* Naamruimte [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)