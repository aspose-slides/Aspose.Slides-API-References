---
title: BinarySearch()
second_title: Aspose.Slides för C++ API-referens
description: Utför binärsökning på ett sorterat omfång.
type: docs
weight: 14
url: /sv/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) funktion

Utför binärsökning på ett sorterat omfång.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i omfånget |
| TComparable | Typen av det jämförbara värdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det sorterade omfånget att söka i |
| comparable | const TComparable\& | Värdet att söka efter |

### Returvärde

[Index](../../system/index/) av det hittade elementet, eller bitvis komplement av infogningspunkten om inte hittas

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funktion

Utför binärsökning på ett sorterat omfång med en anpassad jämförare.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i omfånget |
| TComparer | Typen av jämförare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Det sorterade omfånget att söka i |
| value | const T\& | Värdet att söka efter |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparatorn att använda för jämförelser |

### Returvärde

[Index](../../system/index/) av det hittade elementet, eller bitvis komplement av infogningspunkten om inte hittas

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) funktion

Utför binärsökning på ett förändringsbart sorterat omfång.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i omfånget |
| TComparable | Typen av det jämförbara värdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det sorterade omfånget att söka i |
| comparable | const TComparable\& | Värdet att söka efter |

### Returvärde

[Index](../../system/index/) av det hittade elementet, eller bitvis komplement av infogningspunkten om inte hittas

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funktion

Utför binärsökning på ett förändringsbart sorterat omfång med en anpassad jämförare.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i omfånget |
| TComparer | Typen av jämförare |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det sorterade omfånget att söka i |
| value | const T\& | Värdet att söka efter |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparatorn att använda för jämförelser |

### Returvärde

[Index](../../system/index/) av det hittade elementet, eller bitvis komplement av infogningspunkten om inte hittas

## Se också

* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)