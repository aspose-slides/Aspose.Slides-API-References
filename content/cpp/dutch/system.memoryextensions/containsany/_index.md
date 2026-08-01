---
title: ContainsAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een read-only span een van twee waarden bevat.
type: docs
weight: 53
url: /nl/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) functie


Controleert of een read-only span een van de twee waarden bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |

### Retourwaarde

true als een van de waarden wordt gevonden in de span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) functie


Controleert of een read-only span een van de drie waarden bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |
| value2 | const T\& | De derde waarde om naar te zoeken |

### Retourwaarde

true als een van de waarden wordt gevonden in de span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) functie


Controleert of een mutable span een van de twee waarden bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De wijzigbare span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |

### Retourwaarde

true als een van de waarden wordt gevonden in de span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) functie


Controleert of een mutable span een van de drie waarden bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de span |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De wijzigbare span waarin gezocht wordt |
| value0 | const T\& | De eerste waarde om naar te zoeken |
| value1 | const T\& | De tweede waarde om naar te zoeken |
| value2 | const T\& | De derde waarde om naar te zoeken |

### Retourwaarde

true als een van de waarden wordt gevonden in de span, false otherwise

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Controleert of een read-only span een waarde uit een andere span bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de spans |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span waarin gezocht wordt |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De span met waarden om naar te zoeken |

### Retourwaarde

true als een van de waarden uit values wordt gevonden in de span, false otherwise

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Controleert of een mutable span een waarde uit een read-only span bevat.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Het type van de elementen in de spans |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De wijzigbare span waarin gezocht wordt |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De read-only span met waarden om naar te zoeken |

### Retourwaarde

true als een van de waarden uit values wordt gevonden in de span, false otherwise

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)