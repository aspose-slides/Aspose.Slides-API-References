---
title: TrimStart()
second_title: Aspose.Slides C++ API Referenciája
description: Eltávolítja a megadott elemet egy típusos span kezdetéről.
type: docs
weight: 391
url: /hu/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) függvény

Eltávolítja a megadott elemet a típusos span elejéről.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A vágandó span |
| trimElement | const T\& | Az eltávolítandó elem |

### Visszatérési érték

Egy új span, amelyben a megadott elem a kezdetéről eltávolításra kerül.

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) függvény

Eltávolítja a megadott elemet egy módosítható típusos span elejéről.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A módosítható span, amelyet vágni kell |
| trimElement | const T\& | Az eltávolítandó elem |

### Visszatérési érték

Egy új span, amelyben a megadott elem a kezdetéről eltávolításra kerül.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Eltávolítja a megadott elemeket a típusos span kezdetéről.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A vágandó span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az eltávolítandó elemek |

### Visszatérési érték

Egy új span, amelyben a megadott elemek a kezdetéről eltávolításra kerültek.

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Eltávolítja a megadott elemeket egy módosítható típusos span kezdetéről.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A módosítható span, amelyet vágni kell |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az eltávolítandó elemek |

### Visszatérési érték

Egy új span, amelyben a megadott elemek a kezdetéről eltávolításra kerültek.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) függvény

Eltávolítja a szóköz karaktereket a karakter span elejéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A vágandó karakter span |

### Visszatérési érték

Egy új span, amelyben a szóköz karakterek a kezdetéről eltávolításra kerültek.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) függvény

Eltávolítja a szóköz karaktereket egy módosítható karakter span elejéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet vágni kell |

### Visszatérési érték

Egy új span, amelyben a szóköz karakterek a kezdetéről eltávolításra kerültek.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) függvény

Eltávolítja a megadott karaktert a karakter span elejéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A karakter span, amelyet szűrni kell |
| trimchar | char16_t | Az eltávolítandó karakter |

### Visszatérési érték

Egy új span, amelyben a megadott karakter a kezdetéről eltávolításra került.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) függvény

Eltávolítja a megadott karaktert egy módosítható karakter span elejéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet vágni kell |
| trimchar | char16_t | Az eltávolítandó karakter |

### Visszatérési érték

Egy új span, amelyben a megadott karakter a kezdetéről eltávolításra került.

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) függvény

Eltávolítja a megadott karaktereket a karakter span elejéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A karakter span, amelyet szűrni kell |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Az eltávolítandó karakterek |

### Visszatérési érték

Egy új span, amelyben a megadott karakterek a kezdetéről eltávolításra kerültek.

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) függvény

Eltávolítja a megadott karaktereket egy módosítható karakter span elejéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet vágni kell |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Az eltávolítandó karakterek |

### Visszatérési érték

Egy új span, amelyben a megadott karakterek a kezdetéről eltávolításra kerültek.

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)