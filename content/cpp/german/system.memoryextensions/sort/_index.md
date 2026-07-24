---
title: Sort()
second_title: Aspose.Slides für C++ API-Referenz
description: Sortiert ein Span mithilfe eines benutzerdefinierten Vergleichers.
type: docs
weight: 339
url: /de/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function


Sortiert ein [Span](../../system/span/) mithilfe eines benutzerdefinierten Vergleichers.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer object |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to sort |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

## System::MemoryExtensions::Sort(Span\<T\>\&) function


Sortiert ein [Span](../../system/span/) mit der Standardvergleich.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to sort |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function


Sortiert Schlüssel-Wert-Paare mithilfe eines benutzerdefinierten Vergleichers (Schlüssel und Werte werden zusammen sortiert)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |
| TComparer | The type of the comparer object |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort (maintaining correspondence with keys) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function


Sortiert Schlüssel-Wert-Paare mithilfe eines Vergleichs-Delegaten.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function


Sortiert Schlüssel-Wert-Paare mit der Standardvergleich.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [Span](../../system/span/)
* Klasse [Comparison](../../system/comparison/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)