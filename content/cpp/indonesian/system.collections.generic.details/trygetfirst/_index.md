---
title: TryGetFirst()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba mendapatkan elemen pertama dari koleksi.
type: docs
weight: 248
url: /id/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) fungsi

Mencoba mendapatkan elemen pertama dari koleksi.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen koleksi. |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Koleksi yang akan diambil elemennya. |
| found | **bool**\& | Parameter output. Mengembalikan true ketika koleksi berisi setidaknya satu elemen. Jika tidak, false yang dikembalikan. |

### Nilai Kembalian

Mengembalikan elemen pertama koleksi. Nilai default dari tipe akan dikembalikan bila koleksi kosong.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) fungsi

Mencoba mendapatkan elemen pertama dari koleksi yang memenuhi fungsi predikat.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen koleksi. |

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Koleksi yang akan diambil elemennya. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Fungsi predikat. |
| found | **bool**\& | Parameter output. Mengembalikan true ketika koleksi berisi setidaknya satu elemen. Jika tidak, false yang dikembalikan. |

### Nilai Kembalian

Mengembalikan elemen pertama koleksi. Nilai default dari tipe akan dikembalikan bila tidak ada elemen yang memenuhi fungsi predikat yang ditentukan.

## Lihat Juga

* Kelas [IEnumerable](../../system.collections.generic/ienumerable/)
* Kelas [Func](../../system/func/)
* Ruang Nama [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)