---
title: BinarySearch()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een binaire zoekopdracht uit op een gesorteerde span.
type: docs
weight: 14
url: /nl/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) functie


Voert een binaire zoekopdracht uit op een gesorteerde span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |
| TComparable | Het type van de vergelijkbare waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De gesorteerde span om te doorzoeken |
| comparable | const TComparable\& | De waarde om naar te zoeken |

### Retourwaarde

[Index](../../system/index/) van het gevonden element, of bitwise complement van het invoegpunt indien niet gevonden

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) functie


Voert een binaire zoekopdracht uit op een gesorteerde span met een aangepaste comparer.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |
| TComparer | Het type van de comparer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De gesorteerde span om te doorzoeken |
| value | const T\& | De waarde om naar te zoeken |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | De comparer die moet worden gebruikt voor vergelijkingen |

### Retourwaarde

[Index](../../system/index/) van het gevonden element, of bitwise complement van het invoegpunt indien niet gevonden

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) functie


Voert een binaire zoekopdracht uit op een mutabele gesorteerde span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |
| TComparable | Het type van de vergelijkbare waarde |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De gesorteerde span om te doorzoeken |
| comparable | const TComparable\& | De waarde om naar te zoeken |

### Retourwaarde

[Index](../../system/index/) van het gevonden element, of bitwise complement van het invoegpunt indien niet gevonden

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) functie


Voert een binaire zoekopdracht uit op een mutabele gesorteerde span met een aangepaste comparer.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen in de span |
| TComparer | Het type van de comparer |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De gesorteerde span om te doorzoeken |
| value | const T\& | De waarde om naar te zoeken |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | De comparer die moet worden gebruikt voor vergelijkingen |

### Retourwaarde

[Index](../../system/index/) van het gevonden element, of bitwise complement van het invoegpunt indien niet gevonden

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)