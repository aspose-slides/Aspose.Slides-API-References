---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API-referencia
description: Megkeresi a két span közötti közös előtag hosszát.
type: docs
weight: 27
url: /hu/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi a közös előtag hosszát két span között.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi a közös előtag hosszát egy módosítható span és egy csak olvasható span között.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A csak olvasható span |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) függvény


Megkeresi a közös előtag hosszát két módosítható span között.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Az első módosítható span |
| other | const [Span](../../system/span/)\<T\>\& | A második módosítható span |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) függvény


Megkeresi a közös előtag hosszát két span között egy egyéni egyenlőség-összehasonlító segítségével.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |
| TEqualityComparer | Az egyenlőség-összehasonlító típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Az elemek összehasonlításához használandó egyenlőség-összehasonlító |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) függvény


Megkeresi a közös előtag hosszát egy módosítható span és egy csak olvasható span között egy egyéni egyenlőség-összehasonlító segítségével.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |
| TEqualityComparer | Az egyenlőség-összehasonlító típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A csak olvasható span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Az elemek összehasonlításához használandó egyenlőség-összehasonlító |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) függvény


Megkeresi a közös előtag hosszát két módosítható span között egy egyéni egyenlőség-összehasonlító segítségével.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanok elemeinek típusa |
| TEqualityComparer | Az egyenlőség-összehasonlító típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Az első módosítható span |
| other | const [Span](../../system/span/)\<T\>\& | A második módosítható span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | Az elemek összehasonlításához használandó egyenlőség-összehasonlító |

### Visszatérési érték

Az elemek száma, amelyek mindkét span elején egyeznek.


## Lásd még

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)