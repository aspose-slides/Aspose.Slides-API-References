---
title: BinarySearch()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan pencarian biner pada array yang diurutkan.
type: docs
weight: 612
url: /id/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Melakukan pencarian biner pada array yang diurutkan.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Array terurut untuk melakukan pencarian |
| item | const T\& | Item yang akan dicari |

### Nilai Kembali

[Index](../../index/) dari item yang dicari jika ditemukan, jika tidak, integer negatif yang merupakan komplemen bitwise dari indeks item berikutnya yang lebih besar dari item yang dicari atau, jika tidak ada item yang lebih besar, komplemen bitwise dari jumlah elemen dalam array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metode


BELUM DIIMPLEMENTASIKAN.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Array](../)
* Kelas [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)