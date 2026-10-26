---
title: CheckDiffForAny()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa bahwa setiap elemen koleksi mematuhi predikat.
type: docs
weight: 27
url: /id/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metode

Memeriksa bahwa setiap elemen koleksi mematuhi predikat.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikat untuk diperiksa. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Nilai untuk diperiksa. |

### Nilai Kembali

True jika pemeriksaan berhasil untuk elemen apa pun, false jika semuanya lulus.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)