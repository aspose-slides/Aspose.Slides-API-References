---
title: ContainsAnyExcept()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda read-only span obsahuje jakýkoli prvek kromě tří specifikovaných hodnot.
type: docs
weight: 66
url: /cs/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkce


Kontroluje, zda ReadOnlySpan obsahuje jakýkoli prvek kromě tří specifikovaných hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |
| value2 | const T\& | Třetí hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadaných hodnot, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funkce


Kontroluje, zda mutable span obsahuje jakýkoli prvek kromě tří specifikovaných hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |
| value2 | const T\& | Třetí hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadaných hodnot, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce


Kontroluje, zda ReadOnlySpan obsahuje jakýkoli prvek kromě dvou specifikovaných hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadaných hodnot, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) funkce


Kontroluje, zda mutable span obsahuje jakýkoli prvek kromě dvou specifikovaných hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value0 | const T\& | První hodnota k vyloučení |
| value1 | const T\& | Druhá hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadaných hodnot, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funkce


Kontroluje, zda ReadOnlySpan obsahuje jakýkoli prvek kromě jedné specifikované hodnoty.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadané hodnoty, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) funkce


Kontroluje, zda mutable span obsahuje jakýkoli prvek kromě jedné specifikované hodnoty.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value | const T\& | Hodnota k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek odlišný od zadané hodnoty, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Kontroluje, zda ReadOnlySpan obsahuje jakýkoli prvek kromě těch, které jsou v jiném spanu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span hodnot k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek, který není ve values, jinak false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Kontroluje, zda mutable span obsahuje jakýkoli prvek kromě těch, které jsou v read-only spanu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ReadOnlySpan hodnot k vyloučení |

### Návratová hodnota

true, pokud je nalezen jakýkoli prvek, který není ve values, jinak false

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)