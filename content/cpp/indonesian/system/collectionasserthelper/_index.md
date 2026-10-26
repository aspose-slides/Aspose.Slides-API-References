---
title: CollectionAssertHelper
second_title: Referensi API Aspose.Slides untuk C++
description: API Helper untuk operasi terkait koleksi.
type: docs
weight: 1548
url: /id/system/collectionasserthelper/
---
## CollectionAssertHelper struct

API Helper untuk operasi terkait koleksi.

```cpp
class CollectionAssertHelper
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Memeriksa bahwa semua elemen koleksi memenuhi predikat. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Memeriksa bahwa ada elemen koleksi yang memenuhi predikat. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Menyerialisasi dua koleksi untuk representasi pesan. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Mengonversi koleksi menjadi string dengan menggabungkan representasi string dari elemen-elemen. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Menghitung 'diff' antara dua koleksi. Untuk setiap elemen dari masing-masing koleksi sebagai kunci, nilai hasil akan positif jika elemen muncul lebih banyak kali dalam koleksi "expected", negatif jika elemen muncul lebih banyak kali dalam koleksi "actual", dan nol jika elemen muncul jumlah yang sama di tiap koleksi. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Memformat string untuk digunakan sebagai teks pesan. |
## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)