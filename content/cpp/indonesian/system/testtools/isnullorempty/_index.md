---
title: IsNullOrEmpty()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah koleksi bernilai null atau kosong.
type: docs
weight: 27
url: /id/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) metode


Memeriksa apakah koleksi bernilai null atau kosong.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe koleksi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Koleksi yang akan diperiksa. |

### Nilai Kembalian

True jika koleksi bernilai null atau memiliki jumlah elemen nol, false jika tidak.

## TestTools::IsNullOrEmpty(const System::String\&) metode


Memeriksa apakah string bernilai null atau kosong.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) untuk diperiksa. |

### Nilai Kembalian

True jika string bernilai null atau memiliki panjang nol, false jika tidak.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Struktur [TestTools](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)