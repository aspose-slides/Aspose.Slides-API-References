---
title: MakeDiff()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung 'diff' antara dua koleksi. Untuk setiap elemen masing masing koleksi sebagai kunci, nilai hasil akan menjadi positif jika elemen muncul lebih banyak kali di koleksi \"expected\", negatif jika elemen muncul lebih banyak kali di koleksi \"actual\", dan nol jika elemen muncul jumlah yang sama di tiap koleksi.
type: docs
weight: 1
url: /id/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metode

Menghitung 'diff' antara dua koleksi. Untuk setiap elemen masing-masing koleksi sebagai kunci, nilai hasil akan menjadi positif jika elemen muncul lebih banyak kali di koleksi \"expected\", negatif jika elemen muncul lebih banyak kali di koleksi \"actual\", dan nol jika elemen muncul sama banyak kali di tiap koleksi.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe elemen koleksi yang diharapkan. |
| T2 | Tipe elemen koleksi aktual. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Koleksi yang diharapkan. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Koleksi aktual. |

### Nilai Kembali

Map hasil per-nilai sesuai aturan di atas.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Dictionary](../../../system.collections.generic/dictionary/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [CollectionAssertHelper](../)
* Ruang nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)