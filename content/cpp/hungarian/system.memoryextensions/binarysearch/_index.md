---
title: BinarySearch()
second_title: Aspose.Slides C++ API Referencia
description: Bináris keresést hajt végre egy rendezett spanen.
type: docs
weight: 14
url: /hu/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) függvény

Bináris keresést hajt végre egy rendezett spanen.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |
| TComparable | Az összehasonlítható érték típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő rendezett span |
| comparable | const TComparable\& | A keresendő érték |

### Visszatérési érték

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) függvény

Bináris keresést hajt végre egy rendezett spanen egy egyéni összehasonlító használatával.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |
| TComparer | Az összehasonlító típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő rendezett span |
| value | const T\& | A keresendő érték |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Az összehasonlításhoz használandó összehasonlító |

### Visszatérési érték

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) függvény

Bináris keresést hajt végre egy módosítható rendezett spannen.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |
| TComparable | Az összehasonlítható érték típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő rendezett span |
| comparable | const TComparable\& | A keresendő érték |

### Visszatérési érték

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) függvény

Bináris keresést hajt végre egy módosítható rendezett spannen egy egyéni összehasonlító használatával.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A span elemeinek típusa |
| TComparer | Az összehasonlító típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő rendezett span |
| value | const T\& | A keresendő érték |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Az összehasonlításhoz használandó összehasonlító |

### Visszatérési érték

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## Lásd még

* Típusdefiníció [SharedPtr](../../system/sharedptr/)
* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtere [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)