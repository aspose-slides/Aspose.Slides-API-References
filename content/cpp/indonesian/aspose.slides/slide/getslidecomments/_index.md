---
title: GetSlideComments()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.
type: docs
weight: 209
url: /id/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metode

Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Penulis komentar yang akan dicari atau null untuk mengembalikan semua komentar. |

### Nilai Kembalian

Array dari [Comment](../../comment/).

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [ICommentAuthor](../../icommentauthor/)
* Kelas [Slide](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)