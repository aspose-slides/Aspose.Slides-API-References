---
title: TrimEnd()
second_title: Aspose.Slides for C++ API Referenciája
description: Eltávolítja a megadott elemet a típusos span végéről.
type: docs
weight: 378
url: /hu/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) függvény


Eltávolítja a megadott elemet a típusos span végéről.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A szűrendő span |
| trimElement | const T\& | A szűrendő elem |

### Visszatérési érték

Egy új span, amelyben a megadott elem eltávolításra került a végéről

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) függvény


Eltávolítja a megadott elemet a módosítható típusos span végéről.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A módosítható span, amelyet szűrni kell |
| trimElement | const T\& | A szűrendő elem |

### Visszatérési érték

Egy új span, amelyben a megadott elem eltávolításra került a végéről

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Eltávolítja a megadott elemeket a típusos span végéről.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A szűrendő span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A szűrendő elemek |

### Visszatérési érték

Egy új span, amelyben a megadott elemek eltávolításra kerültek a végéről

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Eltávolítja a megadott elemeket a módosítható típusos span végéről.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | A módosítható span, amelyet szűrni kell |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A szűrendő elemek |

### Visszatérési érték

Egy új span, amelyben a megadott elemek eltávolításra kerültek a végéről

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) függvény


Eltávolítja az üres karaktereket egy karakter span végéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A szűrendő karakter span |

### Visszatérési érték

Egy új span, amelyben az üres karakterek eltávolításra kerültek a végéről

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) függvény


Eltávolítja az üres karaktereket egy módosítható karakter span végéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet szűrni kell |

### Visszatérési érték

Egy új span, amelyben az üres karakterek eltávolításra kerültek a végéről

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) függvény


Eltávolítja a megadott karaktert egy karakter span végéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A szűrendő karakter span |
| trimchar | char16_t | A szűrendő karakter |

### Visszatérési érték

Egy új span, amelyben a megadott karakter eltávolításra került a végéről

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) függvény


Eltávolítja a megadott karaktert egy módosítható karakter span végéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet szűrni kell |
| trimchar | char16_t | A szűrendő karakter |

### Visszatérési érték

Egy új span, amelyben a megadott karakter eltávolításra került a végéről

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) függvény


Eltávolítja a megadott karaktereket egy karakter span végéről.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A szűrendő karakter span |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A szűrendő karakterek |

### Visszatérési érték

Egy új span, amelyben a megadott karakterek eltávolításra kerültek a végéről

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) függvény


Eltávolítja a megadott karaktereket egy módosítható karakter span végéről.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | A módosítható karakter span, amelyet szűrni kell |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A szűrendő karakterek |

### Visszatérési érték

Egy új span, amelyben a megadott karakterek eltávolításra kerültek a végéről

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)