---
title: GetSlideComments()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.
type: docs
weight: 118
url: /id/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method

Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Penulis komentar yang ingin dicari atau null untuk mengembalikan semua komentar. |

### Nilai Kembali

Array dari [IComment](../../icomment/).

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [ICommentAuthor](../../icommentauthor/)
* Kelas [ISlide](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)