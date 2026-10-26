---
title: ContainsAny()
second_title: Aspose.Slides dla C++ – Referencja API
description: Sprawdza, czy span tylko do odczytu zawiera dowolną z dwóch wartości.
type: docs
weight: 53
url: /pl/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja

Sprawdza, czy span tylko do odczytu zawiera dowolną z dwóch wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span do przeszukania |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |

### Wartość zwracana

true jeśli dowolna z wartości zostanie znaleziona w spanie, false w przeciwnym razie

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkcja

Sprawdza, czy span tylko do odczytu zawiera dowolną z trzech wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span do przeszukania |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |
| value2 | const T\& | Trzecia wartość do wyszukania |

### Wartość zwracana

true jeśli dowolna z wartości zostanie znaleziona w spanie, false w przeciwnym razie

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) funkcja

Sprawdza, czy zmienny span zawiera dowolną z dwóch wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny span do przeszukania |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |

### Wartość zwracana

true jeśli dowolna z wartości zostanie znaleziona w spanie, false w przeciwnym razie

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funkcja

Sprawdza, czy zmienny span zawiera dowolną z trzech wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny span do przeszukania |
| value0 | const T\& | Pierwsza wartość do wyszukania |
| value1 | const T\& | Druga wartość do wyszukania |
| value2 | const T\& | Trzecia wartość do wyszukania |

### Wartość zwracana

true jeśli dowolna z wartości zostanie znaleziona w spanie, false w przeciwnym razie

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Sprawdza, czy span tylko do odczytu zawiera dowolną wartość z innego spana.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span do przeszukania |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span wartości do wyszukania |

### Wartość zwracana

true jeśli dowolna wartość z values zostanie znaleziona w spanie, false w przeciwnym razie

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Sprawdza, czy zmienny span zawiera dowolną wartość z spana tylko do odczytu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zmienny span do przeszukania |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span tylko do odczytu z wartościami do wyszukania |

### Wartość zwracana

true jeśli dowolna wartość z values zostanie znaleziona w spanie, false w przeciwnym razie

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)