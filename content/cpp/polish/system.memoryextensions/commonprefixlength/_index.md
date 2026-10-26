---
title: CommonPrefixLength()
second_title: Aspose.Slides dla C++ – referencja API
description: Znajduje długość wspólnego prefiksu pomiędzy dwoma zakresami.
type: docs
weight: 27
url: /pl/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy dwoma zakresami.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy zakres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi zakres |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy zmiennym zakresem a zakresem tylko do odczytu.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny zakres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres tylko do odczytu |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy dwoma zmiennymi zakresami.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Pierwszy zmienny zakres |
| other | const [Span](../../system/span/)\<T\>\& | Drugi zmienny zakres |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy dwoma zakresami przy użyciu własnego komparatora równości.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |
| TEqualityComparer | Typ komparatora równości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy zakres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi zakres |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Komparator równości używany do porównywania elementów |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy zmiennym zakresem a zakresem tylko do odczytu przy użyciu własnego komparatora równości.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |
| TEqualityComparer | Typ komparatora równości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny zakres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres tylko do odczytu |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Komparator równości używany do porównywania elementów |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkcja

Znajduje długość wspólnego prefiksu pomiędzy dwoma zmiennymi zakresami przy użyciu własnego komparatora równości.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |
| TEqualityComparer | Typ komparatora równości |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Pierwszy zmienny zakres |
| other | const [Span](../../system/span/)\<T\>\& | Drugi zmienny zakres |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Komparator równości używany do porównywania elementów |

### Wartość zwracana

Liczba pasujących elementów na początku obu zakresów

## Zobacz także

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)