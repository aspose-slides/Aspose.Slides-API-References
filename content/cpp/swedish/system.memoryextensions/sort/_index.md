---
title: Sort()
second_title: Aspose.Slides för C++ API-referens
description: Sorterar ett Span med en anpassad jämförare.
type: docs
weight: 339
url: /sv/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) funktion

Sorterar en [Span](../../system/span/) med en anpassad jämförare.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |
| TComparer | Typen av jämförelseobjektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Intervallet att sortera |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smartpekare till jämförelseobjektet för elementjämförelse |

## System::MemoryExtensions::Sort(Span\<T\>\&) funktion

Sorterar en [Span](../../system/span/) med standardjämförelse.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i intervallet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Intervallet att sortera |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) funktion

Sorterar nyckel-värde-par med en anpassad jämförare (nycklar och värden sorteras tillsammans)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |
| TComparer | Typen av jämförelseobjektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Nyckelintervallet att sortera |
| values | [Span](../../system/span/)\<TValue\>\& | Värdeintervallet att sortera (behåller korrespondens med nycklar) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smartpekare till jämförelseobjektet för nyckeljämförelse |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) funktion

Sorterar nyckel-värde-par med en jämförelsedelegat.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Nyckelintervallet att sortera |
| values | [Span](../../system/span/)\<TValue\>\& | Värdeintervallet att sortera |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegat för nyckeljämförelse |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) funktion

Sorterar nyckel-värde-par med standardjämförelse.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av nycklar |
| TValue | Typen av värden |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Nyckelintervallet att sortera |
| values | [Span](../../system/span/)\<TValue\>\& | Värdeintervallet att sortera |

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [Span](../../system/span/)
* Klass [Comparison](../../system/comparison/)
* Namnrymd [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)