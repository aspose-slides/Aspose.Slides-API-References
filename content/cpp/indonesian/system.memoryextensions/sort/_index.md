---
title: Sort()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengurutkan sebuah Span menggunakan pembanding khusus.
type: docs
weight: 339
url: /id/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) fungsi

Mengurutkan sebuah [Span](../../system/span/) menggunakan pembanding khusus.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer object |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to sort |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

## System::MemoryExtensions::Sort(Span\<T\>\&) fungsi

Mengurutkan sebuah [Span](../../system/span/) menggunakan perbandingan default.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to sort |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) fungsi

Mengurutkan pasangan kunci-nilai menggunakan pembanding khusus (kunci dan nilai diurutkan bersama)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |
| TComparer | The type of the comparer object |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort (maintaining correspondence with keys) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) fungsi

Mengurutkan pasangan kunci-nilai menggunakan delegasi perbandingan.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegasi untuk perbandingan kunci |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) fungsi

Mengurutkan pasangan kunci-nilai menggunakan perbandingan default.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [Span](../../system/span/)
* Kelas [Comparison](../../system/comparison/)
* Ruang nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)