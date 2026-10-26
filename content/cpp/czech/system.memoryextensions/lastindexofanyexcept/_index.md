---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides pro C++ – reference API
description: Najde poslední výskyt libovolného prvku kromě tří určených hodnot ve spanu.
type: docs
weight: 235
url: /cs/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě tří zadaných hodnot ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |
| value2 | const T\& | Třetí hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě tří zadaných hodnot v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |
| value2 | const T\& | Třetí hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě dvou zadaných hodnot ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě dvou zadaných hodnot v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě zadané hodnoty ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

Najde poslední výskyt libovolného prvku kromě zadané hodnoty v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Najde poslední výskyt libovolného prvku kromě hodnot ze sekvence ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence hodnot k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Najde poslední výskyt libovolného prvku kromě hodnot ze sekvence v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence hodnot k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

Najde poslední výskyt libovolného prvku kromě hodnot z měnitelné sekvence v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| values | const [Span](../../system/span/)\<T\>\& | Sekvence hodnot k vyloučení |

### Návratová hodnota

Nulový index posledního nevyřazeného prvku, nebo -1, pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)