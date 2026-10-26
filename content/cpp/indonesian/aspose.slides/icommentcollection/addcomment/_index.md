---
title: AddComment()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan komentar baru di akhir koleksi.
type: docs
weight: 14
url: /id/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metode

Menambahkan komentar baru di akhir koleksi.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks polos dari komentar baru. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dalam presentasi tempat menambahkan komentar baru. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | [System::DateTime](../../../system/datetime/) | Waktu pembuatan komentar. |

### Nilai Kembali

Komentar yang ditambahkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComment](../../icomment/)
* Kelas [String](../../../system/string/)
* Kelas [ISlide](../../islide/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Kelas [DateTime](../../../system/datetime/)
* Kelas [ICommentCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)