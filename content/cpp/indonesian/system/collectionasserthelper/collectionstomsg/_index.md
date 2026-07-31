---
title: CollectionsToMsg()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyerialkan dua koleksi untuk representasi pesan.
type: docs
weight: 53
url: /id/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metode

Menyerialkan dua koleksi untuk representasi pesan.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe elemen koleksi yang diharapkan. |
| T2 | Tipe elemen koleksi yang sebenarnya. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | String kustom yang disisipkan sebelum nilai yang diharapkan dalam pesan yang dihasilkan |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Koleksi yang diharapkan. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Koleksi yang sebenarnya. |

### Nilai Kembalian

Pesan yang mudah dipahami tentang isi koleksi.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [CollectionAssertHelper](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)