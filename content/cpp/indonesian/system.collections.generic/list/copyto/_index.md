---
title: CopyTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin elemen daftar ke dalam elemen array yang sudah ada.
type: docs
weight: 209
url: /id/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metode


Menyalin elemen daftar ke dalam elemen array yang sudah ada.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Array tujuan. |
| arrayIndex | int | Indeks awal array tujuan. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metode


Menyalin semua elemen ke dalam elemen array yang sudah ada.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) untuk menyalin elemen ke dalam. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metode


Menyalin elemen mulai dari indeks yang ditentukan ke dalam elemen array yang sudah ada.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis 0 dari elemen dalam daftar yang diwakili oleh objek saat ini untuk memulai penyalinan |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) untuk menyalin elemen ke dalam. |
| arrayIndex | int | Posisi awal dalam array tujuan. |
| count | int | Jumlah elemen yang akan disalin. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)