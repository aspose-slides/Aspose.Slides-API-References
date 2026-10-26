---
title: LastIndexOfAny()
second_title: Aspose.Slides pro C++ API Reference
description: Najde poslední výskyt některé ze tří zadaných hodnot ve spanu.
type: docs
weight: 222
url: /cs/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkce

Najde poslední výskyt některé ze tří zadaných hodnot ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledat |
| value1 | const T\& | Druhá hodnota, kterou hledat |
| value2 | const T\& | Třetí hodnota, kterou hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) funkce

Najde poslední výskyt některé ze tří zadaných hodnot v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledat |
| value1 | const T\& | Druhá hodnota, kterou hledat |
| value2 | const T\& | Třetí hodnota, kterou hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt některé ze dvou zadaných hodnot ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledat |
| value1 | const T\& | Druhá hodnota, kterou hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt některé ze dvou zadaných hodnot v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value0 | const T\& | První hodnota, kterou hledat |
| value1 | const T\& | Druhá hodnota, kterou hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Najde poslední výskyt libovolné hodnoty ze sekvence ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence hodnot, které se mají hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Najde poslední výskyt libovolné hodnoty ze sekvence v měnitelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence hodnot, které se mají hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) funkce

Najde poslední výskyt libovolné hodnoty z mutovatelné sekvence v mutabilním spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| values | const [Span](../../system/span/)\<T\>\& | Sekvence hodnot, které se mají hledat |

### Návratová hodnota

Nulově založený index posledního výskytu, nebo -1 pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)