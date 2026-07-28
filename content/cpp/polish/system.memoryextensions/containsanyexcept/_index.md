---
title: ContainsAnyExcept()
second_title: Aspose.Slides dla C++ Odniesienie API
description: Sprawdza, czy niezmienny span zawiera jakikolwiek element oprócz trzech określonych wartości.
type: docs
weight: 66
url: /pl/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Sprawdza, czy niezmienny span zawiera jakikolwiek element oprócz trzech określonych wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy wyszukiwać |
| value0 | const T\& | Pierwsza wartość do wykluczenia |
| value1 | const T\& | Druga wartość do wykluczenia |
| value2 | const T\& | Trzecia wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonych wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Sprawdza, czy modyfikowalny span zawiera jakikolwiek element oprócz trzech określonych wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Modyfikowalny span, w którym należy wyszukiwać |
| value0 | const T\& | Pierwsza wartość do wykluczenia |
| value1 | const T\& | Druga wartość do wykluczenia |
| value2 | const T\& | Trzecia wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonych wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Sprawdza, czy niezmienny span zawiera jakikolwiek element oprócz dwóch określonych wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy wyszukiwać |
| value0 | const T\& | Pierwsza wartość do wykluczenia |
| value1 | const T\& | Druga wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonych wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Sprawdza, czy modyfikowalny span zawiera jakikolwiek element oprócz dwóch określonych wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Modyfikowalny span, w którym należy wyszukiwać |
| value0 | const T\& | Pierwsza wartość do wykluczenia |
| value1 | const T\& | Druga wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonych wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Sprawdza, czy niezmienny span zawiera jakikolwiek element oprócz określonej wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy wyszukiwać |
| value | const T\& | Wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonej wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

Sprawdza, czy modyfikowalny span zawiera jakikolwiek element oprócz określonej wartości.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Modyfikowalny span, w którym należy wyszukiwać |
| value | const T\& | Wartość do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element różny od określonej wartości, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Sprawdza, czy niezmienny span zawiera jakikolwiek element oprócz tych znajdujących się w innym spanie.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy wyszukiwać |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span wartości do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element, którego nie ma w values, false w przeciwnym wypadku

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Sprawdza, czy modyfikowalny span zawiera jakikolwiek element oprócz tych znajdujących się w niezmiennym spanie.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Modyfikowalny span, w którym należy wyszukiwać |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Niezmienny span wartości do wykluczenia |

### Wartość zwracana

true jeśli zostanie znaleziony dowolny element, którego nie ma w values, false w przeciwnym wypadku

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)