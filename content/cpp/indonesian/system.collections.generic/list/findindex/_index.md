---
title: FindIndex()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari elemen yang memenuhi predikat tertentu.
type: docs
weight: 404
url: /id/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metode


Mencari elemen yang sesuai dengan predikat tertentu.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat untuk memeriksa elemen. |

### Nilai Kembalian

[Index](../../../system/index/) dari elemen yang cocok atau -1 jika tidak ditemukan.

## List::FindIndex(int, System::Predicate\<T\>) metode


Mencari elemen yang sesuai dengan predikat tertentu.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) untuk memulai pencarian dari. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat untuk memeriksa elemen. |

### Nilai Kembalian

[Index](../../../system/index/) dari elemen yang cocok atau -1 jika tidak ditemukan.

## List::FindIndex(int, int, System::Predicate\<T\>) metode


Mencari elemen yang sesuai dengan predikat tertentu.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) untuk memulai pencarian dari. |
| count | int | Jumlah elemen yang akan dilalui. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat untuk memeriksa elemen. |

### Nilai Kembalian

[Index](../../../system/index/) dari elemen yang cocok atau -1 jika tidak ditemukan.

## Lihat Juga

* Typedef [Predicate](../../../system/predicate/)
* Kelas [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)