---
title: SequenceEqual()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of twee ReadOnlySpans identieke elementen in dezelfde volgorde bevatten.
type: docs
weight: 326
url: /nl/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of twee ReadOnlySpans identieke elementen in dezelfde volgorde bevatten.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De eerste span om te vergelijken |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De tweede span om te vergelijken |

### Retourwaarde

true als spans dezelfde lengte hebben en alle elementen gelijk zijn, false anders

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of een [Span](../../system/span/) en [ReadOnlySpan](../../system/readonlyspan/) identieke elementen in dezelfde volgorde bevatten.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te vergelijken |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te vergelijken |

### Retourwaarde

true als spans dezelfde lengte hebben en alle elementen gelijk zijn, false anders

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) functie


Bepaalt of twee ReadOnlySpans gelijke elementen bevatten met behulp van een aangepaste comparer.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |
| TComparer | Het type van het comparer-object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De eerste span om te vergelijken |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De tweede span om te vergelijken |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Slimme pointer naar comparer-object voor elementvergelijking |

### Retourwaarde

true als spans dezelfde lengte hebben en comparer alle elementen gelijk acht, false anders

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) functie


Bepaalt of een [Span](../../system/span/) en [ReadOnlySpan](../../system/readonlyspan/) gelijke elementen bevatten met behulp van een aangepaste comparer.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de spans |
| TComparer | Het type van het comparer-object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te vergelijken |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te vergelijken |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Slimme pointer naar comparer-object voor elementvergelijking |

### Retourwaarde

true als spans dezelfde lengte hebben en comparer alle elementen gelijk acht, false anders

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)