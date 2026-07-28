---
title: Count()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zlicza wystąpienia wartości w odczytywanym zakresie.
type: docs
weight: 118
url: /pl/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) funkcja

Zlicza wystąpienia wartości w odczytywanym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value | const T\& | Wartość, którą należy policzyć |

### Wartość zwracana

Liczba wystąpień wartości w zakresie

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Zlicza wystąpienia zakresu w innym odczytywanym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, którego wystąpienia należy policzyć |

### Wartość zwracana

Liczba wystąpień wartości w zakresie

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) funkcja

Zlicza wystąpienia pojedynczej wartości w Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value | const T\& | Wartość, której wystąpienia należy policzyć |

### Wartość zwracana

Liczba wystąpień wartości w zakresie

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Zlicza wystąpienia ReadOnlySpan<T> w Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres zawierający wartości, których wystąpienia należy policzyć |

### Wartość zwracana

Liczba wystąpień zakresu wartości w docelowym zakresie

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)