---
title: LastIndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam rentang item pada array yang ditentukan oleh indeks mulai dan jumlah elemen dalam rentang tersebut.
type: docs
weight: 703
url: /id/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metode

Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam rentang item pada array yang ditentukan oleh indeks mulai dan jumlah elemen dalam rentang tersebut.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan di |
| value | const [ValueType](../valuetype/)\& | Indeks item yang akan ditentukan |
| startIndex | int | [Index](../../index/) dimana pencarian dimulai |
| count | int | Jumlah elemen rentang yang dicari |

### Nilai Kembalian

[Index](../../index/) dari kemunculan terakhir item yang ditentukan jika item ditemukan, bila tidak -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metode

Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam array mulai dari indeks yang ditentukan.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan di |
| value | const [ValueType](../valuetype/)\& | Indeks item yang akan ditentukan |
| startIndex | int | [Index](../../index/) dimana pencarian dimulai |

### Nilai Kembalian

[Index](../../index/) dari kemunculan terakhir item yang ditentukan jika item ditemukan, bila tidak -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metode

Menentukan indeks kemunculan terakhir dari item yang ditentukan dalam array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan di |
| value | const [ValueType](../valuetype/)\& | Indeks item yang akan ditentukan |

### Nilai Kembalian

[Index](../../index/) dari kemunculan terakhir item yang ditentukan jika item ditemukan, bila tidak -1

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Kelas [Array](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)