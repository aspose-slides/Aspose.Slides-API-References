---
title: Copy()
second_title: Aspose.Slides untuk Referensi API C++
description: Menyalin sejumlah elemen yang ditentukan dari array sumber ke array tujuan.
type: docs
weight: 729
url: /id/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) metode

Menyalin sejumlah elemen yang ditentukan dari array sumber ke array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber ke array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Tampilan array sumber |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber ke tampilan array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| dstArray | System::Details::ArrayView\<DstType\> | Tampilan array tujuan |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber ke tampilan array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Tampilan array sumber |
| dstArray | System::Details::ArrayView\<DstType\> | Tampilan array tujuan |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack ke array tujuan.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array sumber pada stack |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber ke array tujuan pada stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array tujuan pada stack |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack ke array tujuan pada stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array sumber pada stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array tujuan pada stack |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam tampilan array sumber |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Tampilan array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam tampilan array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam tampilan array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber |
| DstType | Tipe elemen dalam tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | System::Details::ArrayView\<DstType\> | Tampilan array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) di dalam tampilan array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam tampilan array tujuan.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam tampilan array sumber |
| DstType | Tipe elemen dalam tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Tampilan array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam tampilan array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | System::Details::ArrayView\<DstType\> | Tampilan array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) di dalam tampilan array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber pada stack |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Array sumber pada stack |
| srcIndex | **int64_t** | [Index](../../index/) di dalam array sumber pada stack yang menunjukkan awal rentang item yang akan disalin |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber |
| DstType | Tipe elemen dalam array tujuan pada stack |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Array tujuan pada stack |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan pada stack untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari array sumber pada stack mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber pada stack |
| DstType | Tipe elemen dalam array tujuan pada stack |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Array sumber pada stack |
| srcIndex | **int64_t** | [Index](../../index/) di dalam array sumber pada stack yang menunjukkan awal rentang item yang akan disalin |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array tujuan pada stack |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan pada stack untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) metode


Menyalin sejumlah elemen yang ditentukan dari tampilan array sumber mulai dari indeks yang ditentukan ke posisi yang ditentukan dalam array tujuan pada stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| SrcType | Tipe elemen dalam array sumber pada stack |
| DstType | Tipe elemen dalam array tujuan pada stack |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Tampilan array sumber |
| srcIndex | **int64_t** | [Index](../../index/) di dalam tampilan array sumber yang menunjukkan awal rentang item yang akan disalin |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Array tujuan pada stack |
| dstIndex | **int64_t** | [Index](../../index/) di dalam array tujuan pada stack untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)