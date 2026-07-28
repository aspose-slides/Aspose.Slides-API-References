---
title: StartsWith()
second_title: Aspose.Slides for C++ API Referenciája
description: Ellenőrzi, hogy a span a megadott értékkel kezdődik-e.
type: docs
weight: 352
url: /hu/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) függvény


Ellenőrzi, hogy a span a megadott értékkel kezdődik-e.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az ellenőrzendő span |
| value | const T\& | Az érték, amelyet a span elején ellenőrizni kell |

### Visszatérési érték

true, ha a span az értékkel kezdődik, egyébként false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Ellenőrzi, hogy a span a megadott értékspan-nel kezdődik-e.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannelemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az ellenőrzendő span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amely a kezdeti ellenőrzéshez szükséges értékeket tartalmazza |

### Visszatérési érték

true, ha a span a értékspan-nel kezdődik, egyébként false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Ellenőrzi, hogy a módosítható span a megadott csak-olvasásra szánt értékspan-nel kezdődik-e.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannelemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Az ellenőrzendő módosítható span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A csak-olvasásra szánt span, amely a ellenőrzendő értékeket tartalmazza |

### Visszatérési érték

true, ha a span a értékspan-nel kezdődik, egyébként false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) függvény


Ellenőrzi, hogy a csak-olvasásra szánt span a megadott módosítható értékspan-nel kezdődik-e.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannelemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az ellenőrzendő csak-olvasásra szánt span |
| value | const [Span](../../system/span/)\<T\>\& | A módosítható span, amely a ellenőrzendő értékeket tartalmazza |

### Visszatérési érték

true, ha a span a értékspan-nel kezdődik, egyébként false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) függvény


Ellenőrzi, hogy a karakter span a megadott értékspan-nel kezdődik-e karakterlánc-összehasonlítás használatával.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Az ellenőrzendő karakterspan |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A karakterspan, amely a ellenőrzendő értékeket tartalmazza |
| comparisonType | [StringComparison](../../system/stringcomparison/) | A végrehajtandó karakterlánc-összehasonlítás típusa |

### Visszatérési érték

true, ha a span a értékspan-nel kezdődik, egyébként false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) függvény


Ellenőrzi, hogy egy karakterlánc span a megadott karaktertömbbel kezdődik-e.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Az ellenőrzendő karakterlánc span |
| val | const char16_t * | A karaktertömb, amelyet a kezdeten ellenőrizni kell |

### Visszatérési érték

true, ha a span a karaktertömbbel kezdődik, egyébként false

## Lásd még

* Enum [StringComparison](../../system/stringcomparison/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Osztály [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)