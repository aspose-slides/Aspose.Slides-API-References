---
title: Sort()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Řadí Span pomocí vlastního komparátoru.
type: docs
weight: 339
url: /cs/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) funkce


Řadí [Span](../../system/span/) pomocí vlastního komparátoru.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |
| TComparer | Typ objektu komparátoru |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, který se má řadit |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Chytrý ukazatel na objekt komparátoru pro porovnání prvků |

## System::MemoryExtensions::Sort(Span\<T\>\&) funkce


Řadí [Span](../../system/span/) pomocí výchozího porovnání.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span, který se má řadit |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) funkce


Řadí páry klíč-hodnota pomocí vlastního komparátoru (klíče a hodnoty jsou řazeny společně)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |
| TComparer | Typ objektu komparátoru |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span klíčů, který se má řadit |
| values | [Span](../../system/span/)\<TValue\>\& | Span hodnot, který se má řadit (s udržením vazby ke klíčům) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Chytrý ukazatel na objekt komparátoru pro porovnání klíčů |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) funkce


Řadí páry klíč-hodnota pomocí delegáta porovnání.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span klíčů, který se má řadit |
| values | [Span](../../system/span/)\<TValue\>\& | Span hodnot, který se má řadit |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegát pro porovnání klíčů |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) funkce


Řadí páry klíč-hodnota pomocí výchozího porovnání.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíčů |
| TValue | Typ hodnot |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span klíčů, který se má řadit |
| values | [Span](../../system/span/)\<TValue\>\& | Span hodnot, který se má řadit |

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [Span](../../system/span/)
* Třída [Comparison](../../system/comparison/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)