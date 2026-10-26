---
title: ToArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat dan mengembalikan array dengan semua komentar.
type: docs
weight: 105
url: /id/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() method

Membuat dan mengembalikan array dengan semua komentar.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Nilai Kembali

Array dari [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) method

Membuat dan mengembalikan array dengan semua komentar dari rentang yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks komentar pertama yang akan dikembalikan. |
| count | **int32_t** | Jumlah komentar yang akan dikembalikan. |

### Nilai Kembali

Array dari [Comment](../../comment/).

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)