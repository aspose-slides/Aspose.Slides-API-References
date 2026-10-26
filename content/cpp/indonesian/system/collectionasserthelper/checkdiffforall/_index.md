---
title: CheckDiffForAll()
second_title: Aspose.Slides untuk Referensi API C++
description: Memeriksa bahwa semua elemen koleksi mematuhi predikat.
type: docs
weight: 14
url: /id/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metode

Memeriksa bahwa semua elemen koleksi mematuhi predikat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikat untuk diperiksa. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Nilai untuk diperiksa. |

### Nilai Kembali

False jika pemeriksaan gagal untuk elemen mana pun, true jika semua lolos.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)