---
title: Contains()
second_title: Aspose.Slides a C++ API hivatkozás
description: Ellenőrzi, hogy egy csak-olvasásra szánt span tartalmaz-e egy meghatározott értéket.
type: docs
weight: 40
url: /hu/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) függvény


Ellenőrzi, hogy a csak-olvasásra szánt span tartalmaz-e egy meghatározott értéket.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| value | const T\& | A keresett érték |

### Visszatérési érték

igaz, ha az érték megtalálható a span-ben, egyébként hamis

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) függvény


Ellenőrzi, hogy a módosítható span tartalmaz-e egy meghatározott értéket.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keresni kell |
| value | const T\& | A keresett érték |

### Visszatérési érték

igaz, ha az érték megtalálható a span-ben, egyébként hamis

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) függvény


Ellenőrzi, hogy egy karakter span tartalmaz-e egy másik karakter span-t a megadott összehasonlítási szabályokkal.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A span, amelyben keresni kell |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A keresett span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A végrehajtandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

igaz, ha az érték megtalálható a span-ben, egyébként hamis

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)