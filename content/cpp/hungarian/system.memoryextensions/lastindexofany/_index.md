---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API-referencia
description: Megkeresi a három megadott érték közül bármelyik utolsó előfordulását egy span-ben.
type: docs
weight: 222
url: /hu/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) függvény


Megkeresi a három megadott érték közül bármelyiknek az utolsó előfordulását a span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) függvény


Megkeresi a három megadott érték közül bármelyiknek az utolsó előfordulását egy módosítható span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény


Megkeresi a két megadott érték közül bármelyiknek az utolsó előfordulását a span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) függvény


Megkeresi a két megadott érték közül bármelyiknek az utolsó előfordulását egy módosítható span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy sorozat bármely értékének az utolsó előfordulását a span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény


Megkeresi egy sorozat bármely értékének az utolsó előfordulását egy módosítható span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) függvény


Megkeresi egy módosítható sorozat bármely értékének az utolsó előfordulását egy módosítható span-ben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### Visszatérési érték

Az utolsó előfordulás nulla alapú indexe, vagy -1 ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)