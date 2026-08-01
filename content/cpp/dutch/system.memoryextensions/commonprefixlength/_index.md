---
title: CommonPrefixLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de lengte van de gemeenschappelijke prefix tussen twee spans.
type: docs
weight: 27
url: /nl/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen twee spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen een mutable span en een read-only span.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen twee mutable spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The first mutable span |
| other | const [Span](../../system/span/)\<T\>\& | The second mutable span |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen twee spans met een aangepaste equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen een mutable span en een read-only span met een aangepaste equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function

Bepaalt de lengte van de gemeenschappelijke prefix tussen twee mutable spans met een aangepaste equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The first mutable span |
| other | const [Span](../../system/span/)\<T\>\& | The second mutable span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Retourwaarde

Het aantal overeenkomende elementen aan het begin van beide spans

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)