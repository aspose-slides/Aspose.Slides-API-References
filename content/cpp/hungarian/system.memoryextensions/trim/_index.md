---
title: Trim()
second_title: Aspose.Slides C++ API referencia
description: Levágja a megadott elemet egy típusos span mindkét végéről.
type: docs
weight: 365
url: /hu/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) függvény

Az adott elemet a típusos span mindkét végéről levágja.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A levágandó span |
| trimElement | T | A levágandó elem |

### Visszatérési érték

Új span, amelyből a megadott elemet mindkét végéről levágásra került

## System::MemoryExtensions::Trim(Span\<T\>\&, T) függvény

Az adott elemet egy módosítható típusú span mindkét végéről levágja.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A levágandó módosítható span |
| trimElement | T | A levágandó elem |

### Visszatérési érték

Új span, amelyből a megadott elemet mindkét végéről levágásra került

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Az adott elemeket a típusos span mindkét végéről levágja.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A levágandó span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A levágandó elemek |

### Visszatérési érték

Új span, amelyből a megadott elemek mindkét végéről levágásra kerültek

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Az adott elemeket egy módosítható típusú span mindkét végéről levágja.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A levágandó módosítható span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A levágandó elemek |

### Visszatérési érték

Új span, amelyből a megadott elemek mindkét végéről levágásra kerültek

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) függvény

A szóköz karaktereket a karakterspan mindkét végéről levágja.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A levágandó karakterspan |

### Visszatérési érték

Új span, amelyből a szóközök mindkét végéről levágásra került

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) függvény

A szóköz karaktereket egy módosítható karakterspan mindkét végéről levágja.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A levágandó módosítható karakterspan |

### Visszatérési érték

Új span, amelyből a szóközök mindkét végéről levágásra került

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)