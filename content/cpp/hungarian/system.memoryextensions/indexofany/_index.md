---
title: IndexOfAny()
second_title: Aspose.Slides C++ API Referencia
description: Megkeresi a két megadott érték közül bármelyik első előfordulásának indexét egy ReadOnlySpan<T>-ben
type: docs
weight: 157
url: /hu/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény


Megkeresi a két megadott érték közül bármelyik első előfordulásának indexét egy ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) függvény


Megkeresi a három megadott érték közül bármelyik első előfordulásának indexét egy ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |
| value2 | const T\& | A harmadik keresett érték |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) függvény


Megkeresi a két megadott érték közül bármelyik első előfordulásának indexét egy Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) függvény


Megkeresi a három megadott érték közül bármelyik első előfordulásának indexét egy Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |
| value2 | const T\& | A harmadik keresett érték |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy span bármely értékének első előfordulásának indexét egy másik ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő értékeket tartalmazó span |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy span bármely értékének első előfordulásának indexét egy Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő értékeket tartalmazó span |

### Visszatérési érték

Az első előfordulás nullától kezdődő indexe, vagy -1, ha nem található

## Lásd még

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)