---
title: Sort()
second_title: Aspose.Slides voor C++ API-referentie
description: Sorteert een Span met een aangepaste comparer.
type: docs
weight: 339
url: /nl/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) functie


Sorteert een [Span](../../system/span/) met een aangepaste comparer.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |
| TComparer | Het type van het comparer object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De span om te sorteren |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Slimme pointer naar comparer object voor elementvergelijking |

## System::MemoryExtensions::Sort(Span\<T\>\&) functie


Sorteert een [Span](../../system/span/) met standaardvergelijking.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van elementen in de span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | De span om te sorteren |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) functie


Sorteert sleutel-waardeparen met een aangepaste comparer (sleutels en waarden samen gesorteerd)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van sleutels |
| TValue | Het type van waarden |
| TComparer | Het type van het comparer object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | De span van sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | De span van waarden om te sorteren (behoud van de overeenkomst met sleutels) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Slimme pointer naar comparer object voor sleutelvergelijking |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) functie


Sorteert sleutel-waardeparen met een vergelijking-delegate.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van sleutels |
| TValue | Het type van waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | De span van sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | De span van waarden om te sorteren |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate voor sleutelvergelijking |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) functie


Sorteert sleutel-waardeparen met standaardvergelijking.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van sleutels |
| TValue | Het type van waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | De span van sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | De span van waarden om te sorteren |

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [Span](../../system/span/)
* Klasse [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)