---
title: Count()
second_title: Aspose.Slides voor C++ API-referentie
description: Telt het aantal voorkomens van een waarde in een read-only span.
type: docs
weight: 118
url: /nl/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) functie

Telt het aantal keren dat value voorkomt in span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value | const T\& | De value om te tellen |

### Retourwaarde

Het aantal keren dat value voorkomt in span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Telt het aantal keren dat een span voorkomt binnen een andere read-only span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarvan de voorkomens worden geteld |

### Retourwaarde

Het aantal keren dat value voorkomt in span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) functie

Telt het aantal voorkomens van een enkele waarde in een Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht wordt |
| value | const T\& | De value waarvan de voorkomens geteld worden |

### Retourwaarde

Het aantal voorkomens van de value in de span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Telt het aantal voorkomens van een ReadOnlySpan<T> in een Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span waarin gezocht wordt |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span die waarden bevat waarvan de voorkomens geteld worden |

### Retourwaarde

Het aantal voorkomens van de value span in de target span

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)