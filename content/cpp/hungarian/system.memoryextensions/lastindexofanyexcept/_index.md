---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API referencia
description: Megkeresi a három megadott értéken kívül eső elem utolsó előfordulását egy span-on belül.
type: docs
weight: 235
url: /hu/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\>) függvény

Megkeresi a három megadott értéken kívül eső elem utolsó előfordulását egy span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |
| value2 | const T\& | A harmadik kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\>) függvény

Megkeresi a három megadott értéken kívül eső elem utolsó előfordulását egy módosítható span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |
| value2 | const T\& | A harmadik kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Megkeresi a két megadott értéken kívül eső elem utolsó előfordulását egy span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) függvény

Megkeresi a két megadott értéken kívül eső elem utolsó előfordulását egy módosítható span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) függvény

Megkeresi a megadott értéken kívül eső elem utolsó előfordulását egy span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const T\& | A kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) függvény

Megkeresi a megadott értéken kívül eső elem utolsó előfordulását egy módosítható span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const T\& | A kizárandó érték |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megkeresi a sorozatban szereplő értékeken kívül eső elem utolsó előfordulását egy span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékek sorozata |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megkeresi a sorozatban szereplő értékeken kívül eső elem utolsó előfordulását egy módosítható span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékek sorozata |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) függvény

Megkeresi a módosítható sorozatban szereplő értékeken kívül eső elem utolsó előfordulását egy módosítható span-on belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| values | const [Span](../../system/span/)\<T\>\& | A kizárandó értékek sorozata |

### Visszatérési érték

A nem kizárt elemek utolsó indexe nullától számítva, vagy -1 ha nem található


## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)