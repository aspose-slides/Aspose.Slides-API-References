---
title: LastIndexOfAny()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Znajduje ostatnie wystąpienie dowolnej z trzech określonych wartości w zakresie.
type: docs
weight: 222
url: /pl/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkcja

Znajduje ostatnie wystąpienie dowolnej z trzech określonych wartości w zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |
| value2 | const T\& | Trzecia wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funkcja

Znajduje ostatnie wystąpienie dowolnej z trzech określonych wartości w mutowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |
| value2 | const T\& | Trzecia wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja

Znajduje ostatnie wystąpienie dowolnej z dwóch określonych wartości w zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) funkcja

Znajduje ostatnie wystąpienie dowolnej z dwóch określonych wartości w mutowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Znajduje ostatnie wystąpienie dowolnej wartości z sekwencji w zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekwencja wartości do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Znajduje ostatnie wystąpienie dowolnej wartości z sekwencji w mutowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekwencja wartości do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) funkcja

Znajduje ostatnie wystąpienie dowolnej wartości z mutowalnej sekwencji w mutowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| values | const [Span](../../system/span/)\<T\>\& | Sekwencja wartości do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia, numerowany od zera, lub -1, jeśli nie znaleziono

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)