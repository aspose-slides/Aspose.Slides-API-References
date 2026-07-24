---
title: CommonPrefixLength()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt die Länge des gemeinsamen Präfixes zwischen zwei Spans.
type: docs
weight: 27
url: /de/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen zwei Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite span |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen einem veränderbaren Span und einem schreibgeschützten Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der read-only span |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen zwei veränderbaren Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der erste mutable span |
| other | const [Span](../../system/span/)\<T\>\& | Der zweite mutable span |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen zwei Spans mithilfe eines benutzerdefinierten Equality Comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |
| TEqualityComparer | Der Typ des Equality Comparers |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Der Equality Comparer, der für den Elementvergleich verwendet wird |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen einem veränderbaren Span und einem schreibgeschützten Span mithilfe eines benutzerdefinierten Equality Comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |
| TEqualityComparer | Der Typ des Equality Comparers |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der read-only span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Der Equality Comparer, der für den Elementvergleich verwendet wird |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) Funktion

Findet die Länge des gemeinsamen Präfixes zwischen zwei veränderbaren Spans mithilfe eines benutzerdefinierten Equality Comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |
| TEqualityComparer | Der Typ des Equality Comparers |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der erste mutable span |
| other | const [Span](../../system/span/)\<T\>\& | Der zweite mutable span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Der Equality Comparer, der für den Elementvergleich verwendet wird |

### Rückgabewert

Die Anzahl der übereinstimmenden Elemente zu Beginn beider Spans

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)