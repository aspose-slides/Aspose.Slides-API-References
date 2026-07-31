---
title: TryGetLast()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencoba mendapatkan elemen terakhir dari koleksi.
type: docs
weight: 261
url: /id/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) fungsi

Mencoba mendapatkan elemen terakhir dari koleksi.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen koleksi. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Koleksi dari mana elemen akan diambil. |
| found | **bool**\& | Parameter output. Mengembalikan true ketika koleksi berisi setidaknya satu elemen. Jika tidak, false dikembalikan. |

### Nilai Kembalian

Mengembalikan elemen terakhir koleksi. Nilai default dari tipe akan dikembalikan ketika koleksi kosong.

## Lihat Juga

* Kelas [IEnumerable](../../system.collections.generic/ienumerable/)
* Ruang nama [System::Collections::Generic::Details](../)
* Pustaka [Aspose.Slides](../../)