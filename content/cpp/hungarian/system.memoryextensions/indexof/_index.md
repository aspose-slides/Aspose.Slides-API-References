---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referencia
description: Megkeresi egy ReadOnlySpan<T> érték indexét egy másik ReadOnlySpan<T>-ben
type: docs
weight: 144
url: /hu/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy ReadOnlySpan<T> érték indexét egy másik ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresett span |

### Visszatérési érték

Az első előfordulás nulla-alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) függvény


Megkeresi egyetlen érték indexét egy ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const T\& | A keresett érték |

### Visszatérési érték

Az első előfordulás nulla-alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy ReadOnlySpan<T> érték indexét egy Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresett span |

### Visszatérési érték

Az első előfordulás nulla-alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) függvény


Megkeresi egyetlen érték indexét egy Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const T\& | A keresett érték |

### Visszatérési érték

Az első előfordulás nulla-alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) függvény


Megkeresi egy ReadOnlySpan<char16_t> érték indexét egy ReadOnlySpan<char16_t>-ben a StringComparison használatával.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A keresett érték |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A használandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

Az első előfordulás nulla-alapú indexe, vagy -1, ha nem található

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)