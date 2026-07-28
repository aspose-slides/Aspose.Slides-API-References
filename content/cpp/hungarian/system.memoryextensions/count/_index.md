---
title: Count()
second_title: Aspose.Slides C++ API Referencia
description: Megszámolja egy érték előfordulásait egy csak olvasható spannen.
type: docs
weight: 118
url: /hu/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) függvény

Megszámolja egy érték előfordulásait egy csak olvasható spannen.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const T\& | A számolandó érték |

### Visszatérési érték

Az érték előfordulásainak száma a span-ban

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megszámolja egy span előfordulásait egy másik csak olvasható spannen.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelynek előfordulásait számolni kell |

### Visszatérési érték

Az érték előfordulásainak száma a span-ban

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) függvény

Megszámolja egyetlen érték előfordulásait egy Span<T>-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const T\& | A számolandó érték előfordulásainak száma |

### Visszatérési érték

Az érték előfordulásainak száma a span-ban

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megszámolja egy ReadOnlySpan<T> előfordulásait egy Span<T)-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelynek értékeit számolni kell |

### Visszatérési érték

A cél span-ban a value span előfordulásainak száma

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)