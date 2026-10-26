---
title: Replace()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle voorkomens van een waarde door een nieuwe waarde in een Span.
type: docs
weight: 287
url: /nl/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) functie

Vervangt alle voorkomens van een waarde door een nieuwe waarde in een [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De span om ter plaatse te wijzigen |
| oldValue | const T\& | De waarde om te zoeken en te vervangen |
| newValue | const T\& | De nieuwe waarde om oldValue mee te vervangen |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) functie

Kopieert elementen van bron naar bestemming, waarbij gespecificeerde waarden tijdens het kopiëren worden vervangen.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De bron [ReadOnlySpan](../../system/readonlyspan/) om vanaf te kopiëren |
| destination | [Span](../../system/span/)\<T\>\& | De bestemming [Span](../../system/span/) om naartoe te kopiëren |
| oldValue | const T\& | De waarde om tijdens het kopiëren te zoeken en te vervangen |
| newValue | const T\& | De nieuwe waarde om oldValue mee te vervangen |

## Zie ook

* Klasse [Span](../../system/span/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)