---
title: IndexOfAnyExcept()
second_title: Aspose.Slides C++ API referencia
description: Megkeresi az első olyan elem indexét, amely nem egyenlő a megadott értékkel egy ReadOnlySpan<T>-ben
type: docs
weight: 170
url: /hu/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a megadott értékkel a ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő tartomány |
| value | const T\& | A keresésből kizárandó érték |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a két megadott érték egyikével a ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő tartomány |
| value0 | const T\& | Az első kizárandó érték a keresésből |
| value1 | const T\& | A második kizárandó érték a keresésből |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a három megadott érték egyikével a ReadOnlySpan<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő tartomány |
| value0 | const T\& | Az első kizárandó érték a keresésből |
| value1 | const T\& | A második kizárandó érték a keresésből |
| value2 | const T\& | A harmadik kizárandó érték a keresésből |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a megadott értékkel a Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő tartomány |
| value | const T\& | A keresésből kizárandó érték |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a két megadott érték egyikével a Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő tartomány |
| value0 | const T\& | Az első kizárandó érték a keresésből |
| value1 | const T\& | A második kizárandó érték a keresésből |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a három megadott érték egyikével a Span<T>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartomány elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő tartomány |
| value0 | const T\& | Az első kizárandó érték a keresésből |
| value1 | const T\& | A második kizárandó érték a keresésből |
| value2 | const T\& | A harmadik kizárandó érték a keresésből |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a megadott értékek bármelyikével egy értéktartományban

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartományok elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő tartomány |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékeket tartalmazó tartomány |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Megkeresi az első olyan elem indexét, amely nem egyenlő a Span<T>-ben lévő értéktartomány bármely értékével

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tartományok elemeinek típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő tartomány |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A kizárandó értékeket tartalmazó tartomány |

### Visszatérési érték

Az első nem egyező elem 0-alapú indexe, vagy -1, ha nincs találat

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)