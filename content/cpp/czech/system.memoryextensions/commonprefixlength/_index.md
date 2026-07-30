---
title: CommonPrefixLength()
second_title: Aspose.Slides pro referenci API C++
description: Zjišťuje délku společného prefixu mezi dvěma span-y.
type: docs
weight: 27
url: /cs/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Zjistí délku společného prefixu mezi dvěma span-y.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Zjistí délku společného prefixu mezi měnitelným span-em a read-only span-em.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Měnitelný span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Read-only span |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) funkce


Zjistí délku společného prefixu mezi dvěma měnitelnými span-y.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | První měnitelný span |
| other | const [Span](../../system/span/)\<T\>\& | Druhý měnitelný span |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkce


Zjistí délku společného prefixu mezi dvěma span-y pomocí uživatelského porovnávače rovnosti.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |
| TEqualityComparer | Typ porovnávače rovnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Porovnávač rovnosti používaný k porovnání prvků |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkce


Zjistí délku společného prefixu mezi měnitelným span-em a read-only span-em pomocí uživatelského porovnávače rovnosti.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |
| TEqualityComparer | Typ porovnávače rovnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Měnitelný span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Read-only span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Porovnávač rovnosti používaný k porovnání prvků |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) funkce


Zjistí délku společného prefixu mezi dvěma měnitelnými span-y pomocí uživatelského porovnávače rovnosti.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span-ích |
| TEqualityComparer | Typ porovnávače rovnosti |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | První měnitelný span |
| other | const [Span](../../system/span/)\<T\>\& | Druhý měnitelný span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Porovnávač rovnosti používaný k porovnání prvků |

### Návratová hodnota

Počet odpovídajících prvků na začátku obou span-ů

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)