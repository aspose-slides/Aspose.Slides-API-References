---
title: Sort()
second_title: Aspose.Slides dla C++ Referencja API
description: Sortuje Span przy użyciu własnego komparatora.
type: docs
weight: 339
url: /pl/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function

Sortuje [Span](../../system/span/) przy użyciu własnego komparatora.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |
| TComparer | Typ obiektu komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres do posortowania |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Inteligentny wskaźnik do obiektu komparatora służącego do porównywania elementów |

## System::MemoryExtensions::Sort(Span\<T\>\&) function

Sortuje [Span](../../system/span/) przy użyciu domyślnego porównania.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Zakres do posortowania |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function

Sortuje pary klucz-wartość przy użyciu własnego komparatora (klucze i wartości sortowane razem)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |
| TComparer | Typ obiektu komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy do posortowania |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości do posortowania (z zachowaniem korelacji z kluczami) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Inteligentny wskaźnik do obiektu komparatora służącego do porównywania kluczy |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function

Sortuje pary klucz-wartość przy użyciu delegata porównania.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy do posortowania |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości do posortowania |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegat do porównywania kluczy |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function

Sortuje pary klucz-wartość przy użyciu domyślnego porównania.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ kluczy |
| TValue | Typ wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Zakres kluczy do posortowania |
| values | [Span](../../system/span/)\<TValue\>\& | Zakres wartości do posortowania |

## Zobacz także

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasa [Span](../../system/span/)
* Klasa [Comparison](../../system/comparison/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)