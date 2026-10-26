---
title: Overlaps()
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy két ReadOnlySpan átfedésben van-e a memóriában anélkül, hogy kiszámolná az eltolást.
type: docs
weight: 274
url: /hu/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megállapítja, hogy két ReadOnlySpan átfedésben van-e a memóriában anélkül, hogy kiszámolná az eltolást.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az elemek típusa a spanokban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span, amelynek átfedését ellenőrzi |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span, amelynek átfedését ellenőrzi |

### Visszatérési érték

true ha a spanok közös memóriahelyet osztanak meg, false egyébként

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megállapítja, hogy egy [Span](../../system/span/) és egy [ReadOnlySpan](../../system/readonlyspan/) átfedésben van-e a memóriában anélkül, hogy kiszámolná az eltolást.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az elemek típusa a spanokban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) amelynek átfedését ellenőrzi |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) amelynek átfedését ellenőrzi |

### Visszatérési érték

true ha a spanok közös memóriahelyet osztanak meg, false egyébként

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) függvény


Megállapítja, hogy két ReadOnlySpan átfedésben van-e a memóriában, és kiszámolja az eltolást.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az elemek típusa a spanokban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span, amelynek átfedését ellenőrzi |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span, amelynek átfedését ellenőrzi |
| elementOffset | **int32_t**\& | Kimeneti paraméter, amely megkapja a spanok közti eltolást, ha átfednek |

### Visszatérési érték

true ha a spanok közös memóriahelyet osztanak meg, false egyébként

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) függvény


Megállapítja, hogy egy [Span](../../system/span/) és egy [ReadOnlySpan](../../system/readonlyspan/) átfedésben van-e a memóriában, és kiszámolja az eltolást.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az elemek típusa a spanokban |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) amelynek átfedését ellenőrzi |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) amelynek átfedését ellenőrzi |
| elementOffset | **int32_t**\& | Kimeneti paraméter, amely megkapja a spanok közti eltolást, ha átfednek |

### Visszatérési érték

true ha a spanok közös memóriahelyet osztanak meg, false egyébként

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)