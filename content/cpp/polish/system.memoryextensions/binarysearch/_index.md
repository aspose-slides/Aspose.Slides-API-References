---
title: BinarySearch()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Wykonuje wyszukiwanie binarne w posortowanym spanie.
type: docs
weight: 14
url: /pl/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) function

Wykonuje wyszukiwanie binarne w posortowanym spanie.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |
| TComparable | Typ porównywalnej wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Posortowany span do przeszukania |
| comparable | const TComparable\& | Wartość do wyszukania |

### Wartość zwracana

[Index](../../system/index/) znalezionego elementu, lub dopełnienie bitowe punktu wstawienia, jeśli nie znaleziono

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function

Wykonuje wyszukiwanie binarne w posortowanym spanie za pomocą własnego komparatora.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |
| TComparer | Typ komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Posortowany span do przeszukania |
| value | const T\& | Wartość do wyszukania |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparator używany do porównań |

### Wartość zwracana

[Index](../../system/index/) znalezionego elementu, lub dopełnienie bitowe punktu wstawienia, jeśli nie znaleziono

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) function

Wykonuje wyszukiwanie binarne w zmiennym, posortowanym spanie.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |
| TComparable | Typ porównywalnej wartości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Posortowany span do przeszukania |
| comparable | const TComparable\& | Wartość do wyszukania |

### Wartość zwracana

[Index](../../system/index/) znalezionego elementu, lub dopełnienie bitowe punktu wstawienia, jeśli nie znaleziono

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function

Wykonuje wyszukiwanie binarne w zmiennym, posortowanym spanie za pomocą własnego komparatora.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |
| TComparer | Typ komparatora |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Posortowany span do przeszukania |
| value | const T\& | Wartość do wyszukania |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparator używany do porównań |

### Wartość zwracana

[Index](../../system/index/) znalezionego elementu, lub dopełnienie bitowe punktu wstawienia, jeśli nie znaleziono

## Zobacz także

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)