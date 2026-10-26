---
title: Sort()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengurutkan elemen dalam array yang ditentukan menggunakan pembanding default.
type: docs
weight: 742
url: /id/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) method

Mengurutkan elemen dalam array yang ditentukan menggunakan pembanding default.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array target |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method

Mengurutkan rentang elemen dalam array yang ditentukan menggunakan pembanding default.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array target |
| startIndex | int | Indeks yang menunjukkan awal rentang elemen yang akan diurutkan |
| count | int | Ukuran rentang elemen yang akan diurutkan |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method

Mengurutkan elemen dalam array yang ditentukan menggunakan pembanding yang ditentukan.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array target |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | Objek IComparer<T> yang digunakan untuk membandingkan elemen-elemen array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method

BELUM DIIMPLEMENTASIKAN.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method

Mengurutkan elemen dalam array yang ditentukan menggunakan perbandingan yang ditentukan.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method

Mengurutkan dua array, satu berisi kunci dan yang lainnya - item terkait, berdasarkan nilai array yang berisi kunci, elemen-elemennya dibandingkan menggunakan operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe elemen dalam array **keys** |
| TValue | Tipe elemen dalam array **items** |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) yang berisi nilai kunci |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) yang berisi item yang dipetakan ke nilai kunci dalam array **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method

Mengurutkan dua array, satu berisi kunci dan yang lainnya - item terkait, berdasarkan nilai array yang berisi kunci, elemen-elemennya dibandingkan menggunakan pembanding default.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe elemen dalam array **keys** |
| TValue | Tipe elemen dalam array **items** |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) yang berisi nilai kunci |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) yang berisi item yang dipetakan ke nilai kunci dalam array **keys** |
| index | int | Indeks yang menunjukkan awal rentang yang akan diurutkan |
| length | int | Jumlah elemen dalam rentang yang akan diurutkan |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)