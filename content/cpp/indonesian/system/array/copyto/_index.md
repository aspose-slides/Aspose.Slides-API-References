---
title: CopyTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin semua elemen array saat ini ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen arrayIndex.
type: docs
weight: 118
url: /id/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) metode

Menyalin semua elemen array saat ini ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Array tujuan |
| arrayIndex | int | [Index](../../index/) dalam array tujuan untuk mulai menyisipkan item yang disalin |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const metode

Menyalin semua elemen array saat ini ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) dalam array tujuan untuk mulai menyisipkan item yang disalin |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const metode

Menyalin semua elemen array saat ini ke tampilan array tujuan yang ditentukan. Elemen dimasukkan ke dalam tampilan array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| DstType | Tipe elemen dalam tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Tampilan array tujuan |
| dstIndex | **int64_t** | [Index](../../index/) dalam tampilan array tujuan untuk mulai menyisipkan item yang disalin |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const metode

Menyalin sejumlah elemen yang ditentukan dari array saat ini mulai dari posisi yang ditentukan ke array tujuan yang ditentukan. Elemen dimasukkan ke dalam array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| DstType | Tipe elemen dalam array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array tujuan |
| srcIndex | **int64_t** | [Index](../../index/) dalam array sumber untuk mulai menyalin item |
| dstIndex | **int64_t** | [Index](../../index/) dalam array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const metode

Menyalin sejumlah elemen yang ditentukan dari array saat ini mulai dari posisi yang ditentukan ke tampilan array tujuan yang ditentukan. Elemen dimasukkan ke dalam tampilan array tujuan mulai dari indeks yang ditentukan oleh argumen dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| DstType | Tipe elemen dalam tampilan array tujuan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Tampilan array tujuan |
| srcIndex | **int64_t** | [Index](../../index/) dalam array sumber untuk mulai menyalin item |
| dstIndex | **int64_t** | [Index](../../index/) dalam tampilan array tujuan untuk mulai menyisipkan item yang disalin |
| count | **int64_t** | Jumlah elemen yang akan disalin |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [Array](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)