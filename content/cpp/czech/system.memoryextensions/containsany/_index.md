---
title: ContainsAny()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda read-only span obsahuje některou ze dvou hodnot.
type: docs
weight: 53
url: /cs/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Kontroluje, zda read-only span obsahuje některou ze dvou hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledáme |
| value1 | const T\& | Druhá hodnota, kterou hledáme |

### Návratová hodnota

true, pokud je v spanu nalezena některá z hodnot, false jinak

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkce

Kontroluje, zda read-only span obsahuje některou ze tří hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledáme |
| value1 | const T\& | Druhá hodnota, kterou hledáme |
| value2 | const T\& | Třetí hodnota, kterou hledáme |

### Návratová hodnota

true, pokud je v spanu nalezena některá z hodnot, false jinak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) funkce

Kontroluje, zda mutable span obsahuje některou ze dvou hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledáme |
| value1 | const T\& | Druhá hodnota, kterou hledáme |

### Návratová hodnota

true, pokud je v spanu nalezena některá z hodnot, false jinak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funkce

Kontroluje, zda mutable span obsahuje některou ze tří hodnot.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledáme |
| value1 | const T\& | Druhá hodnota, kterou hledáme |
| value2 | const T\& | Třetí hodnota, kterou hledáme |

### Návratová hodnota

true, pokud je v spanu nalezena některá z hodnot, false jinak

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Kontroluje, zda read-only span obsahuje některou hodnotu z jiného spanu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span hodnot, které se mají hledat |

### Návratová hodnota

true, pokud je v spanu nalezena některá hodnota z values, false jinak

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Kontroluje, zda mutable span obsahuje některou hodnotu z read-only spanu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Read-only span hodnot, které se mají hledat |

### Návratová hodnota

true, pokud je v spanu nalezena některá hodnota z values, false jinak

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)