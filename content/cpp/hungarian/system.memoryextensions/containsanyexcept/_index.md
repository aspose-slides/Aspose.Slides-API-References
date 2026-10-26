---
title: ContainsAnyExcept()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely három megadott értéken kívül esik.
type: docs
weight: 66
url: /hu/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely három megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |
| value2 | const T\& | A harmadik kizárandó érték |

### Visszatérési érték

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Ellenőrzi, hogy egy módosítható span tartalmaz-e olyan elemet, amely három megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keresni kell |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |
| value2 | const T\& | A harmadik kizárandó érték |

### Visszatérési érték

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely két megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |

### Visszatérési érték

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function


Ellenőrzi, hogy egy módosítható span tartalmaz-e olyan elemet, amely két megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keresni kell |
| value0 | const T\& | Az első kizárandó érték |
| value1 | const T\& | A második kizárandó érték |

### Visszatérési érték

true if any element different from the specified values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function


Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely egy megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| value | const T\& | A kizárandó érték |

### Visszatérési érték

true if any element different from the specified value is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function


Ellenőrzi, hogy egy módosítható span tartalmaz-e olyan elemet, amely egy megadott értéken kívül esik.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keresni kell |
| value | const T\& | A kizárandó érték |

### Visszatérési érték

true if any element different from the specified value is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely egy másik spanban nem szereplő érték.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A spanelek elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékek spanja |

### Visszatérési érték

true if any element not in values is found, false otherwise

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Ellenőrzi, hogy egy módosítható span tartalmaz-e olyan elemet, amely egy csak olvasható spanban nem szereplő érték.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A spanelek elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keresni kell |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékek csak olvasható spanele |

### Visszatérési érték

true if any element not in values is found, false otherwise

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)