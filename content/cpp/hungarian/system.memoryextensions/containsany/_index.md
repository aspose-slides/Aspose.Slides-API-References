---
title: ContainsAny()
second_title: Aspose.Slides for C++ API Referencia
description: Ellenőrzi, hogy egy csak olvasható spannel tartalmaz-e bármelyik a két érték közül.
type: docs
weight: 53
url: /hu/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy csak olvasható spannel tartalmaz-e bármelyik a két érték közül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy csak olvasható spannel tartalmaz-e bármelyik a három érték közül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |
| value2 | const T\& | A harmadik keresett érték |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy módosítható spannel tartalmaz-e bármelyik a két érték közül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő módosítható span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy módosítható spannel tartalmaz-e bármelyik a három érték közül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spanben lévő elemek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő módosítható span |
| value0 | const T\& | Az első keresett érték |
| value1 | const T\& | A második keresett érték |
| value2 | const T\& | A harmadik keresett érték |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Ellenőrzi, hogy egy csak olvasható spannel tartalmaz-e bármilyen értéket egy másik spannél.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresett értékek spanja |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Ellenőrzi, hogy egy módosítható spannel tartalmaz-e bármilyen értéket egy csak olvasható spannél.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő módosítható span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A csak olvasható értékek spanja |

### Visszatérési érték

true ha a spanben megtalálható bármelyik érték, false egyébként

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)