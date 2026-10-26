---
title: LastIndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam seluruh daftar.
type: docs
weight: 469
url: /id/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metode

Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam seluruh daftar.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | const T\& | Objek yang akan dicari dalam daftar |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir item dalam seluruh [List](../), jika ditemukan; jika tidak, -1.

## List::LastIndexOf(const T\&, int32_t) const metode

Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](../) yang dimulai dari elemen pertama hingga indeks yang ditentukan.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | const T\& | Objek yang akan dicari dalam daftar |
| index | **int32_t** | Indeks awal berbasis nol dari pencarian mundur. |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir item dalam rentang elemen di [List](../) yang dimulai dari elemen pertama hingga index, jika ditemukan; jika tidak, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metode

Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan terakhir dalam rentang elemen di [List](../) yang berisi jumlah elemen yang ditentukan dan berakhir pada indeks yang ditentukan.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | const T\& | Objek yang akan dicari dalam [List](../) |
| index | **int32_t** | Indeks awal berbasis nol dari pencarian mundur. |
| count | **int32_t** | Jumlah elemen dalam bagian yang akan dicari. |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir item dalam rentang elemen di [List](../) yang berisi count jumlah elemen dan berakhir pada index, jika ditemukan; jika tidak, -1.

## Lihat Juga

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)