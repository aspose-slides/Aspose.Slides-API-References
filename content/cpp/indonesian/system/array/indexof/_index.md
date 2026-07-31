---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array.
type: docs
weight: 131
url: /id/system/array/indexof/
---
## Array::IndexOf(const T\&) const method

Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | const T\& | Item yang indeksnya akan ditentukan |

### Nilai Kembali

[Index](../../index/) dari kemunculan pertama item yang ditentukan jika item ditemukan, selain itu -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method

Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan |
| value | const [ValueType](../valuetype/)\& | Item yang indeksnya akan ditentukan |

### Nilai Kembali

[Index](../../index/) dari kemunculan pertama item yang ditentukan jika item ditemukan, selain itu -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method

Menentukan indeks kemunculan pertama dari item yang ditentukan dalam array mulai dari indeks yang ditentukan.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan |
| value | const [ValueType](../valuetype/)\& | Item yang indeksnya akan ditentukan |
| startIndex | int | [Index](../../index/) dimana pencarian dimulai |

### Nilai Kembali

[Index](../../index/) dari kemunculan pertama item yang ditentukan jika item ditemukan, selain itu -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method

Menentukan indeks kemunculan pertama dari item yang ditentukan dalam rentang item array yang ditentukan oleh indeks mulai dan jumlah elemen dalam rentang.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ArrayType | Tipe elemen dalam array target |
| ValueType | tipe item yang akan dicari dalam array |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) untuk mencari item yang ditentukan |
| value | const [ValueType](../valuetype/)\& | Item yang indeksnya akan ditentukan |
| startIndex | int | [Index](../../index/) dimana pencarian dimulai |
| count | int | Jumlah elemen dalam rentang yang akan dicari |

### Nilai Kembali

[Index](../../index/) dari kemunculan pertama item yang ditentukan jika item ditemukan, selain itu -1

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)